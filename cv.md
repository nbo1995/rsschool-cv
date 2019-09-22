# rsschool-cv
## 1. Sergey Stepanenko
### 2. Contact Info:
  - phone number, viber and WhatsApp +79172129577
  - email: nbo1995@gmail.com
  - page on VK: https://vk.com/nbo95
### 3. Summary:
My goal is to be a good Junior Developer in <Epam>, is to always do what I like and bring joy to others (especially my family). I like work 
computers and build websites. Web development is a kind of designer for me. Now I work in Cinnabon and Яндекс Еда (Yandex food) 
but most of all I want to write websites.It was really interesting for me to create some simple sites with the help of HTML and CSS basic 
courses in the Ubemy and Html academy
### 4. Skills:
- Master the Basics of HTML5 & CSS3 courses: [my certificate](https://www.udemy.com/course/master-the-basics-of-html5-css3-beginner-web-development/?utm_campaign=email&utm_source=sendgrid.com&utm_medium=email)
- Foundations of Front-End Web Development courses: [my certificate](https://www.udemy.com/certificate/UC-4MNU5F5B/?utm_campaign=email&utm_source=sendgrid.com&utm_medium=email)
- Web Development By Doing: HTML / CSS From Scratch courses: [my certificate](https://www.udemy.com/certificate/UC-4DMXER6L/?utm_campaign=email&utm_source=sendgrid.com&utm_medium=email)
- The basics of HTML5 & CSS3 coueses: [my profyle](https://htmlacademy.ru/profile/id1079579)
### 5.Code examples (LATEST):
    - **HTML-code**
  

```<!DOCTYPE html>
<html lang="ru">
<head>
	<meta charset="UTF-8">
	<title>Аккордеон слайдер</title>
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<script src="https://code.jquery.com/jquery-3.2.1.js"></script>
	<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">
	<link rel="stylesheet" href="style.css" type="text/css">
</head>
<body>
<div class="main">
    <h2>Преимущества аккордеон <strong>"слайдера"</strong></h2>
	<div class="panel">
		<div class="panel-heading">
			<a href="#"><i class="fa fa-shopping-cart"></i>Lorem ipsum dolor</a>
		</div>
		<div class="panel-collapse">
			<div class="panel-body">
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet animi architecto consequatur culpa cupiditate debitis delectus ex fugiat in ipsum iure, nemo, neque nobis placeat provident quas quidem ratione reiciendis repellat reprehenderit repudiandae rerum sequi ullam velit voluptatum? Neque, quos!?</p>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate doloribus dolorum ea maxime minima optio perspiciatis quaerat repellendus rerum ullam?</p>
				<h5>Lorem ipsum dolor sit <strong>«amet»: </strong> </h5>
				<div class="wrapper-ul">
					<ul>
						<li>Lorem ipsum:</li>
						<li><a href="#">Ratione reiciendis</a></li>
						<li><a href="#">Lorem ipsum</a></li>
						<li><a href="#">Consectetur adipisicing</a></li>
					</ul>
					<ul>
						<li>Lorem ipsumdolor:</li>
						<li><a href="#">Lorem ipsum</a></li>
						<li><a href="#">Repellat reprehenderit</a></li>
						<li><a href="#">Quidem ratione</a></li>
						<li><a href="#">Velit voluptatum</a></li>
						<li><a href="#">Debitis delectus</a></li>
					</ul>
					<ul>
						<li>Lorem ipsum:</li>
						<li><a href="#">Velit voluptatum</a></li>
						<li><a href="#">Cupiditate debitis</a></li>
						<li><a href="#">Debitis delectus</a></li>
						<li><a href="#">Paceat provident</a></li>
					</ul>
				</div>
				<div class="button"><a href="#">Extended equipment</a></div>
			</div>
		</div>
	</div>
	<div class="panel">
		<div class="panel-heading">
			<a href="#"><i class="fa fa-trophy"></i>Full functional set of CMS</a>
		</div>
		<div class="panel-collapse">
			<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consequatur delectus dolorum eius eos impedit ipsa ipsum labore minus, molestiae nemo nesciunt nulla, optio praesentium quod reprehenderit sit sunt tenetur voluptas:</p>
			<div class="wrapper-ul df">
				<ul>
					<li>Lorem ipsumdolor:</li>
					<li><a href="#">Lorem ipsum</a></li>
					<li><a href="#">Repellat reprehenderit</a></li>
					<li><a href="#">Quidem ratione</a></li>
					<li><a href="#">Velit voluptatum</a></li>
					<li><a href="#">Debitis delectus</a></li>
				</ul>
			</div>
			<div class="button"><a href="#">Additional modules</a></div>

		</div>
	</div>
	<div class="panel">
		<div class="panel-heading">
			<a href="#"><i class="fa fa-server"></i>Several basic advantages</a>
		</div>
		<div class="panel-collapse">
			<div class="panel-body">
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ab amet cum, debitis fugiat molestiae nisi, placeat provident quos ratione sunt tempore totam ullam velit. Consequuntur ex incidunt labore quae quos tempora, voluptatibus? Autem culpa dicta dolorum eaque error eveniet nam odio suscipit tenetur, voluptates! Ad atque maiores officiis quasi sequi!</p>
				<div class="button"><a href="#">Подробнее о преимуществах</a></div>

			</div>
		</div>
	</div>
</div>
<script>
	$(document).ready(function () {

		$('.panel-heading').click(function () {
			$(this).toggleClass('in').next().slideToggle();
			$('.panel-heading').not(this).removeClass('in').next().slideUp();
        });

    });
</script>
</body>
</html>
```

  - **CSS code**
```/* -----  google Font  -----*/
@import url('https://fonts.googleapis.com/css?family=Roboto:100,300,400,500,700');

.main {
 font-family: Roboto, sans-serif;
 font-size: 15px;
 color: #777777;
 line-height: 1.4;
 width: 700px;
}
.main a {
 font-weight: 400;
 text-decoration: none;
}
.main h2 {
 font-weight: 400;
 color: #333333;
 font-size: 28px;
 text-transform: uppercase;
}
.main h5 {
 font-size: 20px;
 margin: 10px 0;
}
.main strong {
 color: #0c9ec7;
}
.panel-heading {
 margin-top: 5px;
}
.panel-heading a {
 background: #333333;
 color: #ffffff;
 display: block;
 padding: 10px 40px 10px 15px;
 position: relative;
 transition: 0.3s;
}
.panel-heading a:hover {
 background: #0c5673;
}
.panel-heading a i {
 font-size: 16px;
 width: 30px;
}
.panel-heading a::after {
 content: "\f107";
 font-family: "FontAwesome";
 position: absolute;
 right: 15px;
 transition: 0.3s;
}
.panel-heading.in a::after {
 transform: rotate(180deg);
}
.panel-heading.in a {
 background: #09afdf;
}
.panel-collapse {
 display: none;
 padding-bottom: 20px;
}
.wrapper-ul {
 display: flex;
 justify-content: space-around;
}
.wrapper-ul.df {
 justify-content: flex-start;
}
.wrapper-ul ul {
 margin-top: 5px;
 padding-left: 20px;
 list-style-type: none;
}
.wrapper-ul li {
 position: relative;
}
.wrapper-ul li::before {
 content: '\f105';
 font-family: "FontAwesome";
 position: absolute;
 left: -13px;
 top: 0;
 color: #09afdf;
 transition: 0.5s;
}
.wrapper-ul li a {
 color: #09afdf;
}
.wrapper-ul li:first-child::before {
 content: '';
}
.wrapper-ul li:first-child {
 color: #333333;
 font-weight: 500;
}
.wrapper-ul li a:hover {
 color: #097ca6;
}
.wrapper-ul li:hover::before {
 transform: translateX(4px);
 color: #097ca6;
}
.button {
 margin-top: 20px;
}
.button a {
 background: #09afdf;
 color: #ffffff;
 padding: 8px 25px;
 border-radius: 3px 3px 3px 3px;
 border: 1px solid #0994c4;
 transition: 0.3s;
}
.button a:hover {
 background: #0994c4;
}
```
### 6. Experiance:
I have no experience working as a developer, but I have a lot of experience as a call-center operator selling home Internet and TV, so I just have to work at high speed, in multi-tasking mode and stress resistance. I am also very patient and calm. Therefore, I think it will be very useful for the developer.
### 7. Education:
- **The sovereign communal primary educational complex of the Dzerzhinsky district of Kharkov**    
_2011-2013 years_
Specialty: Information and Communicable Technologies [certificate](https://drive.google.com/open?id=11MW-L_uRWUfsGRuTm_hg9x2_oyQ30cbL)
### 8. English:
My knowledge of English at 2 points out of 5 points.
