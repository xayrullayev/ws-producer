# ws-producer
Soap ws producer
for initialize postgres database

```
CREATE TABLE public.articles (
	article_id int4 NOT NULL,
	title varchar(200) NOT NULL,
	category varchar(100) NOT NULL,
	CONSTRAINT articles_pkey PRIMARY KEY (article_id)
);

INSERT INTO articles (article_id, title, category) VALUES
	(1, 'Java Concurrency', 'Java'),
	(2, 'Spring Boot Getting Started', 'Spring Boot');
  
  ```
