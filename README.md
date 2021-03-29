# QueryDSL (Query Domain Specific Language)
쿼리를 자바 코드로 표현하는 방법.
<pre>
List❮Person❯ persons = queryFactory.selectFrom(person)
  .where(
    person.firstName.eq("John"),
    person.lastName.eq("Doe"))
  .fetch();
</pre>
http://www.querydsl.com
<br/><br/><br/>

## QueryDSL 의존성 추가
http://www.querydsl.com/static/querydsl/4.4.0/reference/html_single/#d0e137
<pre>
    ❮dependency❯
      ❮groupId❯com.querydsl❮/groupId❯
      ❮artifactId❯querydsl-apt❮/artifactId❯
      ❮version❯${querydsl.version}❮/version❯
      ❮scope❯provided❮/scope❯
    ❮/dependency❯
    
    ❮dependency❯
      ❮groupId❯com.querydsl❮/groupId❯
      ❮artifactId❯querydsl-jpa❮/artifactId❯
      ❮version❯${querydsl.version}❮/version❯
    ❮/dependency❯
    
    ❮dependency❯
      ❮groupId❯org.slf4j❮/groupId❯
      ❮artifactId❯slf4j-log4j12❮/artifactId❯
      ❮version❯1.6.1❮/version❯
    ❮/dependency❯
</pre>
<br/><br/><br/><br/>


