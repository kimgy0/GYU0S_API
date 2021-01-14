#### SQL

<hr></hr>

###### 멤버테이블 생성

```sql
create table member(id bigint generated by default as identity, name varchar(255), primary key(id));
```

<img src="C:\Users\user\Desktop\git\자바API\SQL\1.PNG" alt="image-20210115024745077" style="zoom:80%;" />



<center><small>id라는 이름의 (java)에선 Long이지만, sql에서는 bigint<br>
generated by default as identity -> 값을 세팅하지않고 <br>insert하면 db가 들어왔을 때 자동으로 id 값을 채워줍니다.<br>
    </small></center>



###### 테이블 조회

```sql
select * from member;
```

###### value 삽입

```sql
insert into member(name) values('spring')
```

<img src="C:\Users\user\Desktop\git\자바API\SQL\2.PNG" alt="image-20210115024745077" style="zoom:80%;" />

<hr></hr>

<img src="C:\Users\user\Desktop\git\자바API\SQL\3.PNG" alt="image-20210115024745077" style="zoom:80%;" />

<center>👺TIP</center>

<center><small> 보통은 프로젝트 밑의 sql폴더를 생성하고 따로 그 안에 sql확장자 파일을 관리합니다.</small></center>

<img src="C:\Users\user\Desktop\git\자바API\SQL\4.PNG" alt="image-20210115024745077" style="zoom:80%;" />
