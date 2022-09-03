<template>
  <div class="top">
    <div class="top__container container">
      <div class="top__row row justify-content-between">
        <div class="top__col col-12 col-md-3 pl-0">
          <router-link to="/" class="top__geo">
            <span class="iconify" style="color: #b7b7b7" data-icon="akar-icons:location" data-height="24"></span>Санкт-Петербург</router-link
          >
        </div>
        <div class="top__col col-5 d-none d-md-block">
          <div class="top-nav d-flex justify-content-end">
            <router-link to="/pay" class="top-nav__link">Оплата</router-link>
            <router-link to="/delivery" class="top-nav__link">Доставка</router-link>
            <router-link to="/shops" class="top-nav__link">Магазины</router-link>
            <router-link to="/help" class="top-nav__link">Справка</router-link>
          </div>
        </div>
        <div class="top__col d-none col-3 pr-0 d-md-flex justify-content-end">
          <a href="tel:88005001196" class="top__tel">
            <span class="iconify mr-2" data-icon="bx:bx-phone" style="color: #b7b7b7" data-height="18"></span> 8 (800) 500-11-96</a
          >
        </div>
      </div>
    </div>
  </div>
  	<div class="header">
		<div class="header__container container">
			<div class="header__row d-none d-md-flex no-gutters align-items-center">
				<div class="col-2">
					<div class="header__logo"><a href="#"><img src="images/logo.svg" alt=""></a></div>
				</div>
				<div class="col-7 d-flex pl_25 align-items-center">
					<div class="header__catalog_block">
						<button type="button" class="header__catalog_btn btn_blue d-flex align-items-center justify-content-center">
							<!-- <span class="iconify mr-2" data-icon="ph:list" style="color: #fff;" data-height="18"></span> -->
							<div class="cmn-toggle-switch cmn-toggle-switch__htx"><span></span></div>

							<p>Каталог</p>
						</button>
					</div>
					<div class="header__search_block ml-3 mr44">
						<form class="">
					      <input type="search" class="form-control" autocomplete="false" placeholder="Название, артикул...">
					      <input type="submit" class="d-none btn_blue" value="Найти">
					    </form>
					    <!--результаты поиска при введении -->
					    <ul class="list-unstyled mb-0 d-none">
					      <li><a class="dropdown-item d-flex align-items-center gap-2 py-2" href="#">
					        <span class="d-inline-block bg-success rounded-circle" style="width: .5em; height: .5em;"></span>
					        Action
					      </a></li>
					      <li><a class="dropdown-item d-flex align-items-center gap-2 py-2" href="#">
					        <span class="d-inline-block bg-primary rounded-circle" style="width: .5em; height: .5em;"></span>
					        Another action
					      </a></li>
					      <li><a class="dropdown-item d-flex align-items-center gap-2 py-2" href="#">
					        <span class="d-inline-block bg-danger rounded-circle" style="width: .5em; height: .5em;"></span>
					        Something else here
					      </a></li>
					      <li><a class="dropdown-item d-flex align-items-center gap-2 py-2" href="#">
					        <span class="d-inline-block bg-info rounded-circle" style="width: .5em; height: .5em;"></span>
					        Separated link
					      </a></li>
					    </ul>
					     <!--/ результаты поиска -->
					</div>
				</div>
				<div class="col-3 mt-n1">
					<div class="header__auth flex row">
						<div class="header__profile col-4">
							<a href="" class="d-flex flex-wrap justify-content-center"><span class="iconify" data-icon="ph:user" style="color: #2b2d3a;" data-height="32"></span><p>Вход </p></a>
						</div>
						<div class="header__favorite col-4">
							<a href="" class="d-flex flex-wrap justify-content-center"><span class="iconify" data-icon="ph:heart-straight" style="color: #2b2d3a;" data-height="32"></span><p>Избранное</p></a>
						</div>
						<div class="header__cart col-4">
							<a href="" class="d-flex flex-wrap justify-content-center"><span class="iconify" data-icon="ph:shopping-cart-simple" style="color: #2b2d3a;" data-height="32"></span><p>Корзина</p></a>
						</div>
					</div>
				</div>
			</div>
			<div class="header__row row d-none d-md-block">
				<div class="nav d-flex justify-content-center">
					<a href="" class="nav__link">DJ</a>
					<a href="" class="nav__link">Микрофоны</a>
					<a href="" class="nav__link">Студия</a>
					<a href="" class="nav__link">Звук</a>
					<a href="" class="nav__link">Свет</a>
					<a href="" class="nav__link">Клавиши</a>
					<a href="" class="nav__link">Гитары</a>
					<a href="" class="nav__link">Наушники</a>
					<a href="" class="nav__link">Ударные</a>
					<a href="" class="nav__link">Коммутация</a>
					<a href="" class="nav__link">Кейсы</a>
				</div>
			</div>
			
			<!--мобильная шапка-->
			<div class="mobile_header">
				<div class="mobile_header__row row align-items-center d-md-none">
					<div class="col-2">
						<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
					    	<span class="navbar-toggler-icon"></span>
						</button>
					</div>
					<div class="col-8">
						<div class="header__logo d-flex justify-content-center"><a href="#"><img src="images/logo.svg" alt=""></a></div>
					</div>
					<div class="col-2 d-flex justify-content-end">
						<a href="tel:88005001196" class="icon_tel__mobile"></a>
					</div>
				</div>
				<div class="mobile_header__row row align-items-center d-md-none">
					<div class="header__search_block">
						<form class="">
						   <div class="d-flex justify-content-between">
						   		<input type="search" class="form-control" autocomplete="false" placeholder="Название, артикул...">
					      		<input type="submit" class="d-flex d-md-none btn_blue" value="Найти">
						   </div>
					    </form>
					    <ul class="list-unstyled mb-0 d-none">
					      <li><a class="dropdown-item d-flex align-items-center gap-2 py-2" href="#">
					        <span class="d-inline-block bg-success rounded-circle" style="width: .5em; height: .5em;"></span>
					        Action
					      </a></li>
					      <li><a class="dropdown-item d-flex align-items-center gap-2 py-2" href="#">
					        <span class="d-inline-block bg-primary rounded-circle" style="width: .5em; height: .5em;"></span>
					        Another action
					      </a></li>
					      <li><a class="dropdown-item d-flex align-items-center gap-2 py-2" href="#">
					        <span class="d-inline-block bg-danger rounded-circle" style="width: .5em; height: .5em;"></span>
					        Something else here
					      </a></li>
					      <li><a class="dropdown-item d-flex align-items-center gap-2 py-2" href="#">
					        <span class="d-inline-block bg-info rounded-circle" style="width: .5em; height: .5em;"></span>
					        Separated link
					      </a></li>
					    </ul>
					</div>
				</div>
			</div>
			<!--/ мобильная шапка-->
		</div>
		<!--меню десктоп-->
		<div class="menu">
			<div class="menu_container container">
				<ul class="menu__list">
					<li class="menu__list_li">
						<a href="#"><span class="menu__list_icon icon_dj"></span>DJ оборудование</a>
						<!--подменю второго уровня-->
						<div class="menu__sub">
							<ul class="menu__sub_ul">
								<li class="menu__sub_li"><a href="#">DJ контроллеры</a></li>
								<li class="menu__sub_li"><a href="#">DJ микшеры</a></li>
								<li class="menu__sub_li"><a href="#">CD проигрыватели</a></li>
								<li class="menu__sub_li"><a href="#">DJ процессоры эффектов</a></li>
								<li class="menu__sub_li"><a href="#">Виниловые проигрыватели</a></li>
								<li class="menu__sub_li"><a href="#">Запчасти и аксессуары для винила</a></li>
								<li class="menu__sub_li"><a href="#">Звуковые карты для DJ</a></li>
								<li class="menu__sub_li"><a href="#">DJ стойки</a></li>
								<li class="menu__sub_li"><a href="#">DJ рюкзаки, сумки, чехлы, пайки</a></li>
								<li class="menu__sub_li"><a href="#">Диджейские столы</a></li>
								<li class="menu__sub_li">
									<a href="#">DJ аксессуары</a>
									<!--подменю третьего уровня-->
									<div class="menu__sub_2">
										<ul>
											<li class="menu__sub_2_li"><a href="#">Накладки для DJ-оборудования</a></li>
											<li class="menu__sub_2_li"><a href="#">Слипматы</a></li>
											<li class="menu__sub_2_li"><a href="#">Фейдеры и кроссфейдеры</a></li>
											<li class="menu__sub_2_li"><a href="#">Переключатели - кнобы для DJ</a></li>
										</ul>
									</div>
									<!--подменю третьего уровня-->
								</li>
							</ul>
						</div>
						<!--/подменю второго уровня-->
					</li>
					<li class="menu__list_li">
						<a href="#"><span class="menu__list_icon icon_micro"></span>Микрофоны</a>
						<!--подменю второго уровня-->
						<div class="menu__sub">
							<ul class="menu__sub_ul">
								
								<li class="menu__sub_li"><a href="#">DJ процессоры эффектов</a></li>
								<li class="menu__sub_li"><a href="#">Виниловые проигрыватели</a></li>
								<li class="menu__sub_li"><a href="#">Запчасти и аксессуары для винила</a></li>
								<li class="menu__sub_li"><a href="#">Звуковые карты для DJ</a></li>
								<li class="menu__sub_li"><a href="#">DJ стойки</a></li>
								<li class="menu__sub_li"><a href="#">DJ рюкзаки, сумки, чехлы, пайки</a></li>
								<li class="menu__sub_li"><a href="#">Диджейские столы</a></li>
								<li class="menu__sub_li">
									<a href="#">DJ аксессуары</a>
									<!--подменю третьего уровня-->
									<div class="menu__sub_2">
										<ul>
											<li class="menu__sub_2_li"><a href="#">Накладки для DJ-оборудования</a></li>
											<li class="menu__sub_2_li"><a href="#">Слипматы</a></li>
											<li class="menu__sub_2_li"><a href="#">Фейдеры и кроссфейдеры</a></li>
											<li class="menu__sub_2_li"><a href="#">Переключатели - кнобы для DJ</a></li>
										</ul>
									</div>
									<!--подменю третьего уровня-->
								</li>
							</ul>
						</div>
						<!--/подменю второго уровня-->
					</li>
					<li class="menu__list_li"><a href="#"><span class="menu__list_icon icon_studio"></span>Студия</a></li>
					<li class="menu__list_li"><a href="#"><span class="menu__list_icon icon_sound"></span>Звук</a></li>
					<li class="menu__list_li"><a href="#"><span class="menu__list_icon icon_light"></span>Свет</a></li>
					<li class="menu__list_li"><a href="#"><span class="menu__list_icon icon_keys"></span>Клавиши</a></li>
					<li class="menu__list_li"><a href="#"><span class="menu__list_icon icon_ears"></span>Наушники</a></li>
					<li class="menu__list_li"><a href="#"><span class="menu__list_icon icon_udar"></span>Ударные</a></li>
					<li class="menu__list_li"><a href="#"><span class="menu__list_icon icon_comm"></span>Коммутация</a></li>
					<li class="menu__list_li"><a href="#"><span class="menu__list_icon icon_cases"></span>Кейсы</a></li>
					<li class="menu__list_li"><a href="#">Все категории</a></li>
				</ul>
			</div>
		</div>
		<!--/меню десктоп-->
		<!--мобильное  меню -->
		<nav class="navbar navbar-expand-lg navbar-light d-block d-md-none">
			<div class="navbar-collapse_mobile navbar-collapse collapse" id="navbarNavDropdown">
			    <ul class="navbar-nav">
			    	
			      <li class="nav-item">
			        <a class="nav-link" href="#"> <span class="iconify" data-icon="ph:user" style="color: #8B91B4;" data-height="18"></span> Войти</a>
			      </li>
			      <li class="nav-item dropdown">
			        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
			          <span class="iconify" data-icon="ph:list" style="color: #8b91b4; font-size: 18px;" data-height="18"></span>Каталог
			        </a>
			        <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
			          <ul>
				          <li class="menu__list_li"><a href="#"><span class="menu__list_icon icon_dj"></span>DJ оборудование</a></li>
							<li class="menu__list_li"><a href="#"><span class="menu__list_icon icon_micro"></span>Микрофоны</a></li>
							<li class="menu__list_li"><a href="#"><span class="menu__list_icon icon_studio"></span>Студия</a></li>
							<li class="menu__list_li"><a href="#"><span class="menu__list_icon icon_sound"></span>Звук</a></li>
							<li class="menu__list_li"><a href="#"><span class="menu__list_icon icon_light"></span>Свет</a></li>
							<li class="menu__list_li"><a href="#"><span class="menu__list_icon icon_keys"></span>Клавиши</a></li>
							<li class="menu__list_li"><a href="#"><span class="menu__list_icon icon_guitar"></span>Гитары</a></li>
							<li class="menu__list_li"><a href="#"><span class="menu__list_icon icon_ears"></span>Наушники</a></li>
							<li class="menu__list_li"><a href="#"><span class="menu__list_icon icon_udar"></span>Ударные</a></li>
							<li class="menu__list_li"><a href="#"><span class="menu__list_icon icon_comm"></span>Коммутация</a></li>
							<li class="menu__list_li"><a href="#"><span class="menu__list_icon icon_cases"></span>Кейсы</a></li>
							<li class="menu__list_li"><a href="#">Все категории</a></li>
						</ul>
			        </div>
			      </li>
			      <li class="nav-item">
			        <a class="nav-link" href="#"><span class="iconify" data-icon="carbon:favorite" style="color: #8b91b4; font-size: 18px;"></span>Избранное</a>
			      </li>
			      <li class="nav-item">
			        <a class="nav-link" href="#"><span class="iconify" data-icon="ph:buildings" style="color: #8b91b4; font-size: 18px;"></span>Магазины</a>
			      </li>
			      <li class="nav-item">
			        <a class="nav-link" href="#"><span class="iconify" data-icon="fluent:payment-16-regular" style="color: #8b91b4; font-size: 18px;"></span>Оплата</a>
			      </li>
			      <li class="nav-item">
			        <a class="nav-link" href="#"><span class="iconify" data-icon="ph:truck-light" style="color: #8b91b4; font-size: 18px;"></span>Доставка</a>
			      </li>
			      <li class="nav-item">
			        <a class="nav-link" href="#"> <span class="iconify" data-icon="bi:arrow-counterclockwise" style="color: #8b91b4; font-size: 18px;" data-rotate="270deg"></span>Гарантия и возврат</a>
			      </li>
			      <li class="nav-item">
			        <a class="nav-link" href="#"><span class="iconify" data-icon="ph:chat-circle-dots-light" style="color: #8b91b4; font-size: 18px;"></span>Справка</a>
			      </li>
			      <li class="nav-item">
			        <a class="nav-link" href="#"> <span class="iconify" data-icon="healthicons:info-outline" style="color: #8b91b4; font-size: 18px;"></span>О нас</a>
			      </li>
			    </ul>
			</div>
		</nav>
		<!--/мобильное  меню -->
	</div>
</template>

<script>
export default {}
</script>

<style></style>
