# homework-1
First homework
<!DOCTYPE html>
<html lang="ru">
	<head>
		<meta charset="UTF-8" />
		<meta http-equiv="X-UA-Compatible" content="IE=edge" />
		<meta name="viewport" content="width=device-width, initial-scale=1.0" />
		<title>Web Studio</title>
		<link rel="stylesheet" href="./css/styles.css" />
		<link rel="preconnect" href="https://fonts.googleapis.com" />
		<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
		<link href="https://fonts.googleapis.com/css2?family=Raleway:wght@700&display=swap" rel="stylesheet" />
		<link rel="preconnect" href="https://fonts.googleapis.com" />
		<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
		<link
			href="https://fonts.googleapis.com/css2?family=Raleway:wght@700&family=Roboto:wght@400;500;700;900&display=swap"
			rel="stylesheet"
		/>
		<link rel="stylesheet" href="./css/styles.css" />
	</head>
	<body class="page">
		<!-- Шапка -->
		<header class="header">
			<nav class="navigation">
				<a href="./index.html" lang="en" aria-label="Логотип сайта WebStudio" class="logo">
					<span class="accent">Web</span>Studio
				</a>
				<ul class="site-nav list">
					<li><a href="" class="link current">Студия</a></li>
					<li><a href="./portfolio.html" class="link">Портфолио</a></li>
					<li><a href="" class="link">Контакты</a></li>
				</ul>
			</nav>

			<ul class="auth-nav">
				<li><a class="auth-link" href="mailto:info@devstudio.com">info@devstudio.com</a></li>
				<li><a class="auth-link" href="tel:+380961111111">+38 096 111 11 11</a></li>
			</ul>
		</header>
		<main>
			<!-- Баннер с картинкой -->
			<section class="hero">
				<h1 class="hero-title">Эффективные решения для вашего бизнеса</h1>
				<button class="button" type="button">Заказать услугу</button>
			</section>

			<!-- Преимущества -->
			<section class="features">
				<ul class="features-list">
					<li>
						<h3 class="features-list-title">Внимание к деталям</h3>
						<p class="features-list-text">
							Идейные соображения, а также начало повседневной работы по формированию позиции.
						</p>
					</li>

					<li>
						<h3 class="features-list-title">Пунктуальность</h3>
						<p class="features-list-text">
							Задача организации, в особенности же рамки и место обучения кадров влечет за собой.
						</p>
					</li>

					<li>
						<h3 class="features-list-title">Планирование</h3>
						<p class="features-list-text">
							Равным образом консультация с широким активом в значительной степени обуславливает.
						</p>
					</li>

					<li>
						<h3 class="features-list-title">Современные технологии</h3>
						<p class="features-list-text">
							Значимость этих проблем настолько очевидна, что реализация плановых заданий.
						</p>
					</li>
				</ul>
			</section>

			<!-- Секция с примерами работ -->
			<section>
				<h2 class="section-title">Чем мы занимаемся</h2>
				<ul>
					<li>
						<img src="./images/box1.svg" alt="Сотрудник печатает на клавиатуре" width="370" height="294" />
					</li>

					<li>
						<img src="./images/box2.svg" alt="Сотрудник c телефоном в руках" width="370" height="294" />
					</li>

					<li>
						<img src="./images/box3.svg" alt="Сотрудник рисует на планшете" width="370" height="294" />
					</li>
				</ul>
			</section>

			<!-- Члены команды -->
			<section class="members-group">
				<h2 class="section-title">Наша команда</h2>
				<ul>
					<li>
						<img src="./images/1member.svg" alt="Первый член команды" width="270" height="260" />
						<h3 class="member-title">Игорь Демьяненко</h3>
						<p lang="en" class="member-text">Product Designer</p>
					</li>

					<li>
						<img src="./images/2member.svg" alt="Второй член команды" width="270" height="260" />
						<h3 class="member-title">Ольга Репина</h3>
						<p lang="en"class="member-text">Frontend Developer</p>
					</li>

					<li>
						<img src="./images/3member.svg" alt="Третий член команды" width="270" height="260" />
						<h3 class="member-title">Николай Тарасов</h3>
						<p lang="en"class="member-text">Marketing</p>
					</li>

					<li>
						<img src="./images/4member.svg" alt="Четвертый член команды" width="270" height="260" />
						<h3 class="member-title">Михаил Ермаков</h3>
						<p lang="en"class="member-text">UI Designer</p>
					</li>
				</ul>
			</section>
		</main>
		<footer class="footer">
			<a href="./index.html" lang="en" class="logo-1">
				<span class="accent" class="logo">Web</span>Studio
			</a>
			<address>
				<ul>
					<li>
						<a href="https://goo.gl/maps/CviUbPJFQTQComtV8" target="_blank" rel="noopener noreferrer" lang="en" class="link footer-address">
							г. Киев, пр-т Леси Украинки, 26
						</a>
					</li>
					<li><a href="mailto:info@example.com" class="link footer-link">info@example.com</a></li>
					<li><a href="tel:+380991111111" class="link footer-link">+38 099 111 11 11</a></li>
				</ul>
			</address>
		</footer>
	</body>
</html>






.header {
  font-weight: 500;
  font-size: 14px;
  line-height: 1.14;
  letter-spacing: 0.02em;
  border-bottom: 1px solid var(--border-color);

}
.main-header {
  display: flex;
  align-items: center;
}
.link-logo {
  font-family: 'Raleway', sans-serif;
  font-weight: 700;
  font-size: 26px;
  line-height: 1.19;
  letter-spacing: 0.03em;
  color: var(--logo-color);
  margin-left: 215px;
}
.accent {
  color: var(--accent-color);
}
/* Наделение элементов горизонтальной панелью */
.header-line {
  display: flex;
  align-items: center;
}
.head > .list {
  display: flex;
}
.head .menu-link {
  display: block;
  padding-top: 32px;
  padding-bottom: 32px;
}
/* Выставление горизонтали для Студия\Контакты\Портфолио */
.main-nav li:not(:last-child) {
  margin-right: 40px;
}

/* Можно задать так: (тоесть применяется ко второму, третьему четвертому, ибо над первым нет соседа)
 .main-nav li + li {
  margin-left: 40px;
} */

/* Выставление почты и телефона */
.contact-list-link li:not(:last-child) {
  margin-right: 50px;
}

.header-list {
  margin-left: 93px;
}

.menu-link {
  color: var(--main-color);
}
.contact-link {
  color: var(--secondary-color);
  display: flex;
}
.contact-list-link {
  display: flex;
  margin-left: auto;
  margin-right: 215px;
}
.contacts-link {
  color: var(--secondary-color);
}
.menu-link:hover,
.menu-link:focus {
  color: var(--accent-color);
}
.contact-link:hover,
.contact-link:focus {
  color: var(--accent-color);
}
.contacts-link:hover,
.contacts-link:focus {
  color: var(--accent-color);
}

.current {
  color: var(--accent-color);
}
-------------------------------- .container {
  color: #000000;
  /*! outline: 5px px solid pink;}  */
}































































body {
	font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans",
		"Helvetica Neue", sans-serif;
	text-decoration: none;
}

.list {
	list-style: none;
}
.link {
	text-decoration: none;
}
.address {
	font-style: normal;
}
:root {
	--main-font: "Roboto", sans-serif;
	--main-color: #212121;
	--secondary-color: #757575;
	--logo-color: #000000;
	--accent-color: #2196f3;
	--hero-background-color: #2f303a;
	--btn-text-color: #ffffff;
	--team-background-color: #f5f4fa;
	--portfolio-btn-back-color: #f5f4fa;
	--contacts-link-color: rgba(255, 255, 255, 0.6);
}

.page {
	background-color: rgba(255, 255, 255, 1);
}
ul {
	list-style: none;
}

/* цвет логотипа #000000 #2196F3 */
/* цвет заголовков #212121 */
/* цвет текста #757575 */
/* заголовок и кнопка баннера #FFFFFF */

/* подвал: адрес #FFFFFF
следующие два: rgba(255, 255, 255, 0.6) */
.accent {
	color: var(--accent-color);
}
.logo {
	color: var(--logo-color);
	font-family: "Raleway";
	font-style: normal;
	font-weight: 700;
	font-size: 26px;
	line-height: 31px;
	letter-spacing: 0.03em;
	color: #000000;

	text-decoration: none;
}
.hero {
	background-color: rgba(47, 48, 58, 1);
}
.members-group {
	background-color: #f5f4fa;
}

/* Header styles */
.site-nav .link {
	color: var(--main-color);
}
.site-nav .link:hover,
.site-nav .link:focus {
	color: var(--accent-color);
}
.site-nav .link.current {
	color: var(--accent-color);
}

.auth-nav .auth-link {
	color: var(--secondary-color);
}
.auth-nav .auth-link:hover,
.site-nav .link:focus {
	color: var(--accent-color);
}

.section-title {
	color: var(--main-color);
}

.link,
.auth-link {
	text-decoration: none;
	list-style: none;
}

/* hero styles */
.hero-title {
	text-transform: uppercase;
	color: rgba(255, 255, 255, 1);

	font-family: "Roboto";
	font-style: normal;
	font-weight: 900;
	font-size: 44px;
	line-height: 60px;

	text-align: center;
	letter-spacing: 0.06em;
	text-transform: uppercase;

	color: #ffffff;
}
/* button styles */
.button {
	color: var(--btn-text-color);
	background-color: var(--accent-color);
	font-family: "Roboto";
	font-style: normal;
	font-weight: 700;
	font-size: 16px;
	line-height: 30px;
	display: flex;
	align-items: center;
	text-align: center;
	letter-spacing: 0.06em;

	color: #ffffff;
}

/* features styles */
.features-list-title {
	text-transform: uppercase;
	color: var(--main-color);
}

.features-list-title {
	font-family: "Roboto";
	font-style: normal;
	font-weight: 700;
	font-size: 14px;
	line-height: 16px;
	letter-spacing: 0.03em;
	text-transform: uppercase;

	color: #212121;
}

li .features-list-text {
	color: var(--secondary-color);
	font-family: "Roboto";
	font-style: normal;
	font-weight: 400;
	font-size: 14px;
	line-height: 24px;
	letter-spacing: 0.03em;

	color: #757575;
}

/* Members */
.member-title {
	font-family: "Roboto";
	font-style: normal;
	font-weight: 500;
	font-size: 16px;
	line-height: 19px;

	color: #212121;
}
.member-text {
	font-family: "Roboto";
	font-style: normal;
	font-weight: 400;
	font-size: 16px;
	line-height: 19px;

	color: #757575;
}

.footer-link {
	font-family: "Roboto";
	font-style: normal;
	font-weight: 400;
	font-size: 14px;
	line-height: 24px;
	letter-spacing: 0.03em;

	color: rgba(255, 255, 255, 0.6);
}
.footer-address {
	font-family: "Roboto";
	font-style: normal;
	font-weight: 400;
	font-size: 14px;
	line-height: 24px;
	letter-spacing: 0.03em;

	color: #ffffff;
}
.footer {
	background: #2f303a;
}
.logo-1 {
	color: var(--logo-color);
	font-family: "Raleway";
	font-style: normal;
	font-weight: 700;
	font-size: 26px;
	line-height: 31px;
	letter-spacing: 0.03em;
	color: #ffffff;

	text-decoration: none;
}
