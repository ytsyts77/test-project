# 안녕하세요.

개발환경 테스트 수정


[source,java,indent=0]
----
	import org.springframework.boot.*;
	import org.springframework.boot.autoconfigure.*;
	import org.springframework.web.bind.annotation.*;

	@RestController
	@SpringBootApplication
	public class Example {

		@RequestMapping("/")
		String home() {
			return "Hello World!";
		}

		public static void main(String[] args) {
			SpringApplication.run(Example.class, args);
		}

	}
----
