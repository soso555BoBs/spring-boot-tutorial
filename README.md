# 参考資料
- Spring Boot チュートリアル「Spring で REST サービスを構築」
    - https://spring.pleiades.io/guides/tutorials/rest/
- Spring initializer
    - https://start.spring.io/
    - pom.xml を作ってくれるよ

# 雑記
1. 2021/02/12 12:45
    - EmployeeController の実装を進める中で、以下を追記しないといけない
        - ```import static org.springframework.hateoas.server.mvc.WebMvcLinkBuilder.*;```
            - https://spring.pleiades.io/guides/tutorials/rest/#_what_makes_something_restful
            - ドキュメント内では言及されていないので注意
            - ```ControllerLinkBuilder``` は非推奨のため、ググって知っても使わないこと
    - 続き
        - https://spring.pleiades.io/guides/tutorials/rest/#_evolving_rest_apis
2. 2021/02/15 11:48
    - 完了
    - 次はこれ
        - Spring Security および Angular
        - https://spring.pleiades.io/guides/tutorials/spring-security-and-angular-js/