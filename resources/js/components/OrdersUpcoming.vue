<template>
    <ul class="personal-account-orders__list personal-account-card__list">
        <li class="personal-account-orders__col personal-account-card__col">
            <div class="personal-account-orders__card card dt-travel-card">
                <div class="card-header bg-white p-0 position-relative">
                    <div class="card-img">
                        <div class="dt-wrapper-gradient position-absolute"></div>
                        <h5 class="dt-excursion-type">групповая экскурсия</h5>
                        <div class="dt-like d-flex align-items-center justify-content-center">
                            <svg class="opacity-1" xmlns="http://www.w3.org/2000/svg"
                                 xmlns:xlink="http://www.w3.org/1999/xlink" width="18" height="14"
                                 viewBox="0 0 18 14">
                                <image id="done_FILL0_wght600_GRAD0_opsz48" width="18" height="14"
                                       xlink:href="data:img/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAAOCAYAAAAi2ky3AAAAoklEQVQoka3SvwpBYRQA8B/dFAaewztIFhPlCWxeTNmMDBaLwWt4AJOUTfrKV7fbxedeZz2nX+dfY3mcqxEdZLhmNZEtuphUhSIyxh2D5h+QKU6/QmXIISQi1EarKhKhULDD5gP2EYnQECPM3mBfkQjtscCjBEtC8jtal2D9VMTrK+WwEKsXdkYvBSlCRSwZyY9WxMKYt1SkrKM8Fo5wSUHgCWEEMQufwN2RAAAAAElFTkSuQmCC"/>
                            </svg>
                        </div>
                        <img class="dt-excursion__image" src="dist/images/travels/4.jpg" alt="">
                        <div class="dt-price d-flex justify-content-between position-absolute w-100">
                            <h5 class="dt-price__sum text-white align-items-end d-flex">
                                <span class="fw-bold">700 руб.</span>
                                <span class="dt-price__title text-uppercase text-muted-white d-lg-block d-md-block d-none">
                                                        за человека
                                                    </span>
                                <span class="dt-price__title text-uppercase text-muted-white d-block d-md-none">
                                                        за чел.
                                                    </span>
                            </h5>
                            <h5 class="dt-price__time text-uppercase text-muted-white">1 час</h5>
                        </div>
                    </div>
                </div>
                <div class="card-body bg-white">
                    <div class="card-body__excursion-rating d-flex justify-content-between">
                        <div class="dt-rating d-flex">
                            <h5 class="dt-rating__title text-muted-black me-2">рейтинг
                                экскурсии </h5>
                            <h5 class="fw-bold color-black">4.95</h5>
                        </div>
                        <div class="personal-account__stars dt-rating__star d-flex">
                            <img src="dist/images/icons/star_blue.svg" alt="">
                            <img src="dist/images/icons/star_blue.svg" alt="">
                            <img src="dist/images/icons/star_blue.svg" alt="">
                            <img src="dist/images/icons/star_blue.svg" alt="">
                            <img src="dist/images/icons/star_blue.svg" alt="">
                        </div>
                    </div>
                    <div class="card-body__excursion">
                        <div class="card-body__excursion-name">
                            <h4 class="fw-bold">Чарующий пятигорск - город горячих вод</h4>
                        </div>
                        <div class="card-body__excursion-description fw-light">
                            <h5>
                                Приглашаем пройтись по старым паркам и гротам, вообразить как по ту
                                сторону аллеи гуляет Лермонтов, вон в той ...
                            </h5>
                        </div>
                    </div>
                    <div class="personal-account-orders-info card-body__excursion-date d-flex justify-content-between">
                        <div class="personal-account-orders-info__item dt-calendar d-flex align-items-center">
                            <img class="personal-account-orders-info__img me-2"
                                 src="dist/images/icons/calendar_today_FILL0_wght400_GRAD0_opsz48_blue.svg"
                                 alt="calendar" style="width: 18px; height: 16px">
                            <h5 class="personal-account-orders-info__text d-lg-block d-md-block d-none">
                                <div class="personal-account-orders-info__text_grey">
                                    дата начала
                                </div>
                                15 августа в 10:00
                            </h5>
                        </div>
                        <div class="personal-account-orders-info__item dt-calendar d-flex align-items-center">
                            <svg class="personal-account-orders-info__img me-2"
                                 xmlns="http://www.w3.org/2000/svg"
                                 xmlns:xlink="http://www.w3.org/1999/xlink" width="13" height="16"
                                 viewBox="0 0 13 16">
                                <image id="location_on_FILL0_wght400_GRAD0_opsz48" width="13"
                                       height="16"
                                       xlink:href="data:img/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA0AAAAQCAYAAADNo/U5AAABN0lEQVQokYXSP0tcURAF8J+i7YI2GkHsxMIvICwi2kRQ8gFUrGysTBqt7ewWhBQJ2Ii9fxIQi6CmDlikspIgSLTSzkZllnlw9yF6YODdmXPuu2dmuny+U0MDHzGa6Usc46GiddcEq/iHFiYyWplbrUg9hWArCxF7eCouXsBXjGC9Es3gC6bxu/b3EO/iCr9wUnk6xH+s1A3W8B0DlacmDop6NOMoo1Hkg9MMURf6cF0UpzCXMVnkg9MXnp6znUO4yOIpfmbtvBB9CG7laR/3WH7H0w76K0/b2dbxNwRjWAxuuRFhcjgH+lgT9OYzb/Gp3Iho9yC+ZXNKxEtisO2RlBsRt8znjTfYyPwmlrKLwekQBf6k8EeeYxvWsvVRa6MuCsSqzOaWBOL7rCS8JgoEKbYk5vS3o4IXC9BBg8EJGV4AAAAASUVORK5CYII="/>
                            </svg>
                            <h5 class="personal-account-orders-info__text d-lg-block d-md-block d-none">
                                <div class="personal-account-orders-info__text_grey">
                                    место встречи
                                </div>
                                Мечеть в центре посёлка Терскол
                            </h5>
                        </div>
                    </div>
                </div>
                <div class="personal-account-orders-footer card-footer bg-white text-center">
                    <a href="#"
                       class="personal-account-orders-footer__link text-uppercase dt-travel-card__action">
                        <h6 class="dt-btn-text">подробнее</h6>
                    </a>
                    <a href="#"
                       class="personal-account-orders-footer__link text-uppercase dt-travel-card__action">
                        <h6 class="dt-btn-text">написать гиду</h6>
                    </a>
                </div>
            </div>
        </li>
        <li class="personal-account-orders__col_disabled personal-account-orders__col personal-account-card__col">
            <div class="personal-account-orders__card card dt-travel-card">
                <div class="card-header bg-white p-0 position-relative">
                    <div class="card-img">
                        <div class="dt-wrapper-gradient position-absolute"></div>
                        <h5 class="dt-excursion-type">групповая экскурсия</h5>
                        <div class="dt-like d-flex align-items-center justify-content-center">
                            <svg class="opacity-1" xmlns="http://www.w3.org/2000/svg"
                                 xmlns:xlink="http://www.w3.org/1999/xlink" width="14" height="20"
                                 viewBox="0 0 14 20">
                                <image id="autorenew_FILL0_wght600_GRAD0_opsz48" width="14"
                                       height="20"
                                       xlink:href="data:img/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAUCAYAAAC9BQwsAAABXUlEQVQ4jZXTPWtVQRDG8Z83EmOlGATlGlSMYJ+QNlZpJUXEKlhZWAhiIVgIdqa0sdEvEEgacy0iFgGbSPwAKVS4iOILKIaAjaIMzCXrslfiUxz27M7/zOwzcw64+cUQjeAE3reOO8Mo3MNLTP4v+ADfsNGCa3AM1/AkgSi124IPFusprOJ0vn/6V0WdAnqBCdzHKUxnqWHORbyuMx7GCg7hEnp5tpSl19DZ+FhkvIozmalXBNzBTAV1s7LFAOfxO10s9Qsfqr0fadjlTqbu4/MwIwp9zTufjzuOZsb96mfER8a36eKRfYDH0o9+J5v9Md0tdbQBXs8WrsXjEWYTHigqeIVbxV605W4a9jjAXbypoBix0HJe4TbWc+9KMOXIldA5vMPzXEdc/H8L2ce/ZjV0EsdzPZ7nm3iKh9gZBNbgFubwDNu5/t6ytzX98fMGcAE3WlArYwnXc7on/AEsckS7DU5eAAAAAABJRU5ErkJggg=="/>
                            </svg>
                        </div>
                        <img class="dt-excursion__image" src="dist/images/travels/4.jpg" alt="">
                        <div class="dt-price d-flex justify-content-between position-absolute w-100">
                            <h5 class="dt-price__sum text-white align-items-end d-flex">
                                <span class="fw-bold">700 руб.</span>
                                <span class="dt-price__title text-uppercase text-muted-white d-lg-block d-md-block d-none">
                                                        за человека
                                                    </span>
                                <span class="dt-price__title text-uppercase text-muted-white d-block d-md-none">
                                                        за чел.
                                                    </span>
                            </h5>
                            <h5 class="dt-price__time text-uppercase text-muted-white">1 час</h5>
                        </div>
                    </div>
                </div>
                <div class="card-body bg-white">
                    <div class="card-body__excursion-rating d-flex justify-content-between">
                        <div class="dt-rating d-flex">
                            <h5 class="dt-rating__title text-muted-black me-2">рейтинг
                                экскурсии </h5>
                            <h5 class="fw-bold color-black">4.95</h5>
                        </div>
                        <div class="personal-account__stars dt-rating__star d-flex">
                            <img src="dist/images/icons/star_blue.svg" alt="">
                            <img src="dist/images/icons/star_blue.svg" alt="">
                            <img src="dist/images/icons/star_blue.svg" alt="">
                            <img src="dist/images/icons/star_blue.svg" alt="">
                            <img src="dist/images/icons/star_blue.svg" alt="">
                        </div>
                    </div>
                    <div class="card-body__excursion">
                        <div class="card-body__excursion-name">
                            <h4 class="fw-bold">Чарующий пятигорск - город горячих вод</h4>
                        </div>
                        <div class="card-body__excursion-description fw-light">
                            <h5>
                                Приглашаем пройтись по старым паркам и гротам, вообразить как по ту
                                сторону аллеи гуляет Лермонтов, вон в той ...
                            </h5>
                        </div>
                    </div>
                    <div class="personal-account-orders-info card-body__excursion-date d-flex justify-content-between">
                        <div class="personal-account-orders-info__item dt-calendar d-flex align-items-center">
                            <img class="personal-account-orders-info__img me-2"
                                 src="dist/images/icons/calendar_today_FILL0_wght400_GRAD0_opsz48_blue.svg"
                                 alt="calendar" style="width: 18px; height: 16px">
                            <h5 class="personal-account-orders-info__text d-lg-block d-md-block d-none">
                                <div class="personal-account-orders-info__text_grey">
                                    дата начала
                                </div>
                                15 августа в 10:00
                            </h5>
                        </div>
                        <div class="personal-account-orders-info__item dt-calendar d-flex align-items-center">
                            <svg fill="#000" class="personal-account-orders-info__img me-2"
                                 xmlns="http://www.w3.org/2000/svg"
                                 xmlns:xlink="http://www.w3.org/1999/xlink" width="13" height="16"
                                 viewBox="0 0 13 16">
                                <image id="location_on_FILL0_wght400_GRAD0_opsz48" width="13"
                                       height="16"
                                       xlink:href="data:img/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA0AAAAQCAYAAADNo/U5AAABN0lEQVQokYXSP0tcURAF8J+i7YI2GkHsxMIvICwi2kRQ8gFUrGysTBqt7ewWhBQJ2Ii9fxIQi6CmDlikspIgSLTSzkZllnlw9yF6YODdmXPuu2dmuny+U0MDHzGa6Usc46GiddcEq/iHFiYyWplbrUg9hWArCxF7eCouXsBXjGC9Es3gC6bxu/b3EO/iCr9wUnk6xH+s1A3W8B0DlacmDop6NOMoo1Hkg9MMURf6cF0UpzCXMVnkg9MXnp6znUO4yOIpfmbtvBB9CG7laR/3WH7H0w76K0/b2dbxNwRjWAxuuRFhcjgH+lgT9OYzb/Gp3Iho9yC+ZXNKxEtisO2RlBsRt8znjTfYyPwmlrKLwekQBf6k8EeeYxvWsvVRa6MuCsSqzOaWBOL7rCS8JgoEKbYk5vS3o4IXC9BBg8EJGV4AAAAASUVORK5CYII="/>
                            </svg>
                            <h5 class="personal-account-orders-info__text d-lg-block d-md-block d-none">
                                <div class="personal-account-orders-info__text_grey">
                                    место встречи
                                </div>
                                Мечеть в центре посёлка Терскол
                            </h5>
                        </div>
                    </div>
                </div>
                <div class="personal-account-orders-footer card-footer bg-white text-center">
                    <a href="#"
                       class="personal-account-orders-footer__link text-uppercase dt-travel-card__action">
                        <h6 class="dt-btn-text">подробнее</h6>
                    </a>
                    <a href="#"
                       class="personal-account-orders-footer__link text-uppercase dt-travel-card__action">
                        <h6 class="dt-btn-text">написать гиду</h6>
                    </a>
                </div>
            </div>
        </li>
    </ul>
</template>

<script>
export default {
    name: "OrdersUpcoming"
}
</script>

<style scoped>

</style>
