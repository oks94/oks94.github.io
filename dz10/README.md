<!doctype html>
<html lang="ru">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <!-- подключаем свои стили для корректировки отображения на странице -->
    <link rel="stylesheet" href="css/main.css">
    <title>Изучаем Bootstrap 4</title>
  </head>
  <body>
    <!-- навигационная панель -->
      <nav class="navbar navbar-expand-lg navbar-light bg_nav_me fixed-top">
           <a class="navbar-brand" href="#">Poly Dream</a>
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
        
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
              <li class="nav-item active">
                <a class="nav-link" href="#">О компании <span class="sr-only">(current)</span></a>
              </li>
              <li class="nav-item ">
                <a class="nav-link" href="#onas">Советы</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Оплата и доставка</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Контакты</a>
              </li>
            </ul>
            
          
          </div>
            <a href="#" class="btn btn-primary btn-me " data-toggle="modal" data-target="#exampleModal">Корзина</a>
          </div>
          </div>
          
          <!-- Modal -->
<div class="modal fade" id="exampleModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="exampleModalLabel">Отправить заявку для заказа</h5>
          <button type="button" class="close" data-dismiss="modal" aria-label="Close">
            <span aria-hidden="true">&times;</span>
          </button>
        </div>
        <div class="modal-body">
  <!-- форма обратной связи -->
  <form>
    <div class="form-group">
      <label for="exampleInputEmail1">Ваш Email адрес</label>
      <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
      <small id="emailHelp" class="form-text text-muted">Ваши данные не будут переданы третьим лицам</small>
    </div>
    <div class="form-group">
      <label for="exampleInputPassword1">Ваш Пароль</label>
      <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
    </div>
    <div class="form-group form-check">
      <input type="checkbox" class="form-check-input" id="exampleCheck1">
      <label class="form-check-label" for="exampleCheck1">Я Согласен с обработкой моих данных</label>
    </div>
    <button type="submit" class="btn btn-primary">Отправить</button>
  </form>
  
   
  
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-secondary" data-dismiss="modal">Закрыть окно</button>
          
        </div>
      </div>
    </div>
        </nav>
        <!-- ---------------------------------------------------- -->
    <div class="container">

      <div class="row">
        <div class="row-left col-md-4">
            
        </div>
        <div class="row-right col-md-8">
           
        </div>
      </div>
    </div>
      
      
    </div>
    <!-- Карусель начало -->
     <div class="bd-example">
        <div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
          <ol class="carousel-indicators">
            <li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleCaptions" data-slide-to="1"></li>
            <li data-target="#carouselExampleCaptions" data-slide-to="2"></li>
          </ol>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="images/002.jpg" class="d-block w-100" alt="...">
              <div class="carousel-caption d-none d-md-block">
                <h6>ПОЛИГОНАЛЬНЫЕ</h6>
                <h6> СКУЛЬПТУРЫ</h6>
                <p>Мы проектируем полигональные скульптуры из бумаги.</p> 
                    <p>Своими руками мы превращаем виртуальные модели в конструктор.</p>
                    <p>Благодаря этому, любо человек может украсить свой интерьер уникальным элементом дизайна.</p>
                        <p> Наши проекты доступны в следующих трех форматах.</p>
              </div>
            </div>
            <div class="carousel-item">
              <img src="images/003.jpg" class="d-block w-100" alt="...">
              <div class="carousel-caption d-none d-md-block">
                
              </div>
            </div>
            <div class="carousel-item">
              <img src="images/004.jpg" class="d-block w-100" alt="...">
              <div class="carousel-caption d-none d-md-block">
                
              </div>
            </div>
          </div>
          <a class="carousel-control-prev" href="#carouselExampleCaptions" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
          </a>
          <a class="carousel-control-next" href="#carouselExampleCaptions" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
          </a>
        </div>
      </div>
    <!-- карусель окончание -->
    <!-- карточки товаров начало -->
<div class="container-fluid">
    <p id="onas" class="p_hide">Раздел в котором описано кто мы такие</p>
    
    <div class="row justify-content-center">
  <!-- 1-z карточка -->
  <div class="card col-md-3 col-sm-4 m-1 p-0 ">
      <img src="images/005.jpg" class="card-img-top" alt="...">
      <div class="card-body card-img-overlay">
        <h5 class="card-title">Готовые изделия</h5>
        <p class="card-text">Мы можем изготовить любую скульптуру на заказ из бумаги, или подготовить чертежи для наших партнеров,которые соберут модель из металла, пластика или полистерола.</p>
        <a href="#" class="btn btn-primary btn-me stretched-link">Перейти в магазин</a>
        </div>
      </div>
 
  
  <!-- 2-z карточка -->
  <div class="card col-md-3 col-sm-4 m-1 p-0">
        <img src="images/006.jpg" class="card-img-top" alt="...">
        <div class="card-body card-img-overlay">
          <h5 class="card-title">Наборы для склейки</h5>
          <p class="card-text">Прекрасный выбор для себя и в подарок. В набор входят материалы для создания скульптуры: выкройка на дизайнерской бумаге; картон для основания; клей; канцелярский нож; линейка; инструкция.</p>
          <a href="#" class="btn btn-primary btn-me stretched-link">Перейти в магазин</a>
        </div>
      </div>
        <!-- 3-z карточка -->
  
      <div class="card col-md-3 col-sm-4 m-1 p-0 ">
          <img src="images/007.jpg" class="card-img-top" alt="...">
          <div class="card-body card-img-overlay">
            <h5 class="card-title">Файлы</h5>
            <p class="card-text">Для тех, кому интересно собрать полигональную скульптуру полностью самостоятельно, начиная с поиска типографии для печати, подходящего клея и бумаги. При покупке вы получите схемудля печати в формате PDF и инструкцию по сборке.</p>
            <a href="#" class="btn btn-primary btn-me stretched-link" >Перейти в магазин</a>
          </div>
        </div>
          </div>
         
  </div>
  
    <div class="container-fluid">
      <p id="onas" class="p_hide">Раздел в котором описано кто мы такие</p>
      <div class="row justify-content-center">

        <h1>Советы по сборке</h1>
        <div class="row">
            <div class="row justify-content-center">
         
          <div class="col-md-10">
            
              <p><i>Не спешите</i></p>
             
              <p>Мы постарались сделать всё возможное, чтобы процесс сборки был простым и понятным, тем не менее вам потребуется от 4 до 10 часов чтобы собрать одну модель. Не пытайтесь успеть сделать всё сразу. Мы советуем растянуть процесс сборки на два-три вечера, тогда результат получится аккуратнее, а вы получите удовольствие от сборки.</p>
          </div>
          <div class="col-md-10">
              <p><i>Внимательность и аккуратность</i></p>
            
              <p>Для сборки модели не обязательно обладать специфическими навыками работы с бумагой, главное — ваши внимательность и аккуратность. Детям до 12 лет потребуется помощь взрослых для сборки модели.</p>
          </div>
          <div class="col-md-10">
              <p><i>Выбор бумаги</i></p>
      
              <p>Результат напрямую зависит от качества используемых материалов. Пожалуйста, не пытайтесь собрать модель из обычной офисной бумаги. В наших наборах используется качественная бумага с оптимальным соотношением хлопка и целюллозы в составе, благодаря чему она не сильно крошится и расслаивается на сгибах. У этой бумаги есть лёгкая фактура, поэтому места склейки меньше бросаются в глаза на завершённой работе. Если вы покупаете бумагу самостоятельно, советуем вам выбрать фактурную бумагу плотностью 180-250 гр./м².</p>
            </div>
            <div class="col-md-10">
                <p><i>Выбор клея</i></p>
             
              
              <p>В наши наборы для склейки входит клей, произведённый специально по нашему заказу. Он схватывает менее чем за 10 секунд, но этого времени достаточно для корректировки стыка. Время схватывания играет большую роль, потому что на одной модели около 120 мест склейки. Наш клей легко смывается водой с рук. Прозрачный после высыхания. Обратите внимание, что большинство клеев ПВА не подходят для этой деятельности, они долго сохнут и деформируют бумагу. При покупке файлов рекомендуем использовать для сборки резиновый клей, универсальный суперклей Момент, клей для обойных стыков, UHU Twist & Glue или клей Момент Кристалл.</p>
              </div>
                <div class="col-md-10">
              <p><i>Скульптуры можно красить</i></p>
            
              <p>Но не любой краской. От некоторых видов автомобильной краски в баллоне бумага может деформироваться. Лучше использовать акриловую краску в баллоне или любую другую краску не на водной основе.</p>
              
          </div>
        </div>
        <div class="container">
      <p id="onas" class="p_hide">Раздел в котором описано кто мы такие</p>
      <div class="row">
          <div class="row justify-content-center">
        <h1>Доставка</h1>
        
        <div class="row">
          <div class="col-md-4">
              
                <p><i>Готовые изделия</i></p>

                
              <p>Ссылка на скачивание файлов появится автоматически сразу после оплаты заказа. Кроме того, в течение 2 часов на указанный при покупке email придёт письмо со ссылкой на скачивание файлов.</p>
          </div>
          <div class="col-md-4">
              
              <p><i>Наборы для склейки</i></p>
              <p>По Белоруссии: Ориентировочный срок доставки в региональные центры <i>3-5 дней</i>. Максимальный срок доставки: <i>10 дней</i>. Доставка осуществляется из Гомеля.

                  Почтой Беларуси. Единая цена по Белоруссии :<i> 8 BYN</i>. 
                   Стоимость рассчитывается автоматически при оформлении заказа. Адреса пунктов выдачи можно посмотреть по ссылке.
                  Курьером стоимость от <i>15 BYN</i>.
                   </p>
          </div>
          <div class="col-md-4">
        <p><i>Файлы</i></p>
              <p>Модели делаются только на заказ. Срок изготовления модели из бумаги  <i>2-5 дней</i>. Сроки изготовления моделей из других материалов обсуждаются индивидуально.

                  Для доставки модель крепится к стенке коробки так, чтобы она была жёстко зафиксирована. Таким образом, модели приезжают в идеальном состоянии. Время доставки готовых изделий <i>7-10 дней</i> по Белоруссии. Стоимость <i>80-100 BYN</i></p>
            
                  
                </div>
              </div>
            </div>
          </div>
       
        
      
         <!-- форма обратной связи -->
<div class="container">
    <h2>Заполните поля формы</h2>
    <p>Поля отмеченные * (звёздочкой) обязательно заполнить!</p>
    <div class="row justify-content-center my-5">
      <form action="formd.php" method="POST" name="me_form" class="container">
  <!-- <p>Введите Ваше имя:</p> -->
  <input type="text" name="form_name" maxlength="30" class="col-md-3" placeholder="*Введите Ваше имя" required>
  <!-- <p>Введите Ваш телефон:</p> -->
  <input type="text" pattern="[0-9]+" name="form_tel" class="col-md-5" placeholder="*Введите Ваш телефон только цифры: 375251234567" required>
  
  <input type="submit" class="col-md-2" value="Жми">
      </form>
    </div>
  </div>
  
<!-- подвал -->
<div class="container-fluide">
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <a class="navbar-brand" href="#">Poly Dream</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
    
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">О компании <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#onas">Советы</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Оплата и доставка</a>
          </li>
        </ul>
        
    </nav>
    <!-- ---------------------------------------------------- -->
  <div class="row bg-dark">
    <div class="col"></div>
    <div class="col text-light ">Телефон +375(29)111-63-84, email@polydream.com</div>
    <div class="col"></div>
  </div>
  </div>
  


    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
  </body>
</html>
