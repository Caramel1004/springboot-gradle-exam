# springboot-gradle-exam
스프링부트 샘플(연습 프로젝트)<br>
- Springboot 개념 업로드 예정
- 과제테스트 끝나면 정리 할 예정
springboot + jpa + h2 + gradle

@SpringBootApplication:

Spring Boot 애플리케이션의 메인 클래스에 지정합니다.
@Configuration, @EnableAutoConfiguration, @ComponentScan을 함께 포함합니다.
@Controller:

Spring MVC에서 컨트롤러 클래스를 나타냅니다.
HTTP 요청에 대한 처리 메소드가 있는 클래스에 이 Annotation을 붙입니다.
@RestController:

@Controller와 @ResponseBody의 결합으로 RESTful 웹 서비스의 엔드포인트를 처리하는 컨트롤러를 나타냅니다.
@Service:

비즈니스 로직이 있는 서비스 클래스를 나타냅니다.
주로 서비스 레이어의 클래스에 사용됩니다.
@Repository:

데이터 액세스 계층의 리포지토리 (DAO) 클래스를 나타냅니다.
@Autowired:

의존성 주입(Dependency Injection)을 수행하는데 사용됩니다.
해당 필드, 생성자 또는 메소드에 이 Annotation을 붙이면 스프링이 해당 타입의 빈을 주입합니다.
@RequestMapping:

URL 패턴과 메소드를 매핑하여 요청을 처리하는 메소드를 지정합니다.
주로 컨트롤러 클래스의 메소드에 사용됩니다.
@GetMapping, @PostMapping, @PutMapping, @DeleteMapping:

@RequestMapping의 단축어로 HTTP 메소드에 따라 각각 GET, POST, PUT, DELETE 요청을 처리하는 메소드를 지정합니다.
@PathVariable:

경로 변수를 메소드 파라미터에 매핑할 때 사용됩니다.
@RequestBody:

HTTP 요청의 본문(body)을 메소드 파라미터에 매핑할 때 사용됩니다.
주로 POST 요청에서 JSON 데이터를 받을 때 사용됩니다.
@ResponseStatus:

HTTP 응답 상태 코드를 지정할 때 사용됩니다.
@Configuration:

Java 기반의 설정 클래스임을 나타냅니다.
주로 @Bean Annotation과 함께 사용하여 빈을 정의하는 클래스에 붙입니다.
@ComponentScan:

스프링이 컴포넌트를 검색할 패키지를 지정합니다.
@SpringBootApplication에 내장되어 있어 주로 사용자 지정 설정이나 다른 구성 클래스에서 사용됩니다.
@EnableAutoConfiguration:

자동 구성을 활성화합니다. 주로 @SpringBootApplication에 내장되어 있어서 따로 사용할 일은 많이 없습니다.
@Value:

프로퍼티 값을 필드에 주입할 때 사용됩니다.
application.properties 파일이나 환경 변수에서 값을 가져와 필드에 할당합니다.
