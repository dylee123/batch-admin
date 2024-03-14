This is Spring Batch Admin java 1.8

이프로젝트는 Spring Batch 의 Metadata db 정보를 기준으로 Job의 실행 성공 여부를 간단하게 조회할수 있는 Spring Batch Admin 입니다.

이 프로젝트의 구성은 Java 버전 1.8 을 사용했고 Spring Boot로 구성되었습니다.
DB 는 MySql 과 H2 를 사용할수 있습니다.

/src/main/resources/application.properties 파일의 ENVIRONMENT 항목에 db 종류를 설정하고

/src/main/resources/batch-[db].properties 파일에 db 접속정보를 설정합니다.
