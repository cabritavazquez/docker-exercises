```bash
$cd ui-web
$docker build -t lcabrita/ui-web:0.0.1 .

$cd api-web
$docker build -t lcabrita/api-web:0.0.1 .

$docker run -it -d -p 5173:5173 --name ui-web lcabrita/ui-web:0.0.1

$docker run -it -d -p 3000:3000 --name api-web lcabrita/api-web:0.0.1
```