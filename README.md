# 参考資料
- Spring Boot チュートリアル「Spring で REST サービスを構築」
    - https://spring.pleiades.io/guides/tutorials/rest/

# 雑記
1. 2021/02/12 12:45
    - EmployeeController の実装を進める中で、以下を追記しないといけない
        - ```import static org.springframework.hateoas.server.mvc.WebMvcLinkBuilder.*;```
    - ドキュメント内では言及されていないので注意
    - ```ControllerLinkBuilder``` は非推奨のため、ググって知っても使わない
    - 続き
        - https://spring.pleiades.io/guides/tutorials/rest/#_evolving_rest_apis
