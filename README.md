# The-Minimalist-Assignment-
#  HTML

<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
    <script src="https://kit.fontawesome.com/ac42c3b1f7.js" crossorigin="anonymous"></script>
</head>

<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-white">
        <div class="container">

        </div>
    </nav>
    <div class="banner-section-bg-container d-flex justify-content-center flex-column">
        <div class="text-center">
            <h1 class="banner-heading mb-3">The choice is yours. <br />
                Because they don't heve one.</h1>
            <button class="custom-button">QUICK VIEW</button>
        </div>
    </div>

    <h1 class="heading-8">
        <hr class="kk-1" />
        About
        <hr class="kk-2" />
    </h1>
    <div class="To">
        <p class="p-2">
            our products are crafted exclusively from the dreams and screams of young kids who wanted to show their mastery in their <br />
            chosen fields, but were directed towards a factory for daily wages. Each cracker bursts brighter than their lost smiles, and can <br />
            be heard louder than ther their crie for miles. Buy them, burst them, brag about them.
        </p>
    </div>
    <p class="p-3">
        The choice is yours. Because they don't have one.
    </p>
    <h1 class="heading-9">
        <hr class="kk-3" />
        Our products
        <hr class="kk-4" />
    </h1>
    <div class="cards-container">
        <div class="card">
            <div class="card-background-container nike-bg-image-1">
            </div>
            <h4 class="card-heading-1">Raju Rassibomb</h4>
            <button class="custom-button-22">QUICK VIEW</button>
            <div class="card-footer-container">
                <div class="icon-container">
                </div>
            </div>
        </div>
        <div class="card">
            <div class="card-background-container nike-bg-image-2">
            </div>
            <h4 class="card-heading-2">Ladiyon ki Rani chani</h4>
            <button class="custom-button-33">QUICK VIEW</button>
            <div class="card-footer-container">
                <hr class="kk-5" />
            </div>
            <div class="body">
                <h1 class="heading-44">
                    Follow us on
                </h1>
                <img src="https://dundonald.org/wp-content/uploads/2020/03/001-instagram.png" class="logo-1" />
                <img src="https://cdn.flyscoot.com/prod-src/images/default-source/pokemon/social-media-logos/002-youtube.png?sfvrsn=5b124395_2" class="logo-2" />
                <img src="https://cdn.flyscoot.com/prod-src/images/default-source/pokemon/social-media-logos/003-twitter.png?sfvrsn=72dbd6c2_2" class="logo-3" />
                <img src="https://online.swisscasinos.ch/library/General%20Assests/004-facebook.png" class="logo-4" />
                <img src="https://depts.washington.edu/ecc/wordpress/wp-content/uploads/2020/06/005-linkedin.png" class="logo-5" />
            </div>
        </div>
    </div>
</body>

</html>


#  css 


@import url("https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap");

* {
    box-shadow: border-box;
}

body {
    margin: 0px;
}


.banner-section-bg-container {
    background-image: url("https://s3-alpha-sig.figma.com/img/22f6/b7b5/b47561aa2ad560235e2702e286a6d4b7?Expires=1720396800&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=N4RpXidMPsQm7pabNJsO4fatsHc2XZffXb8eFLYsL9exMRLgNBYUbgWUgkb2ljo3OUjWJoq-makvZH7uIRjijNRwhVN4FM~2hp6TTQaoT6qKb6EOif-am~8zGpVTrmDeXWdENqjBUpsOCocAlzNIq8BxxHsIRbzyWGrKTVv6bXtQSXAlIIDviSXybiQg~14rCi3z2kKr~9Hr4B552rizXaX2N6ZA5udDuwQnKcsi0es2K8Q1cIJIEfnkrFXyUY7c4IOgjYnpFH8fkRA-8AD5Wju8UUVGzERkfI1QAHtdvNB0cwamTLa473~dIACN16BiT4-EhE5R0IZXSszuwDMCcQ__");
    width: 1440px;
    height: 527px;
    background-size: cover;
}

@media screen and (min-width: 768px) {
    .banner-section-bg-container {
        background-image: url('https://s3-alpha-sig.figma.com/img/22f6/b7b5/b47561aa2ad560235e2702e286a6d4b7?Expires=1720396800&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=N4RpXidMPsQm7pabNJsO4fatsHc2XZffXb8eFLYsL9exMRLgNBYUbgWUgkb2ljo3OUjWJoq-makvZH7uIRjijNRwhVN4FM~2hp6TTQaoT6qKb6EOif-am~8zGpVTrmDeXWdENqjBUpsOCocAlzNIq8BxxHsIRbzyWGrKTVv6bXtQSXAlIIDviSXybiQg~14rCi3z2kKr~9Hr4B552rizXaX2N6ZA5udDuwQnKcsi0es2K8Q1cIJIEfnkrFXyUY7c4IOgjYnpFH8fkRA-8AD5Wju8UUVGzERkfI1QAHtdvNB0cwamTLa473~dIACN16BiT4-EhE5R0IZXSszuwDMCcQ__');
        width: 1512px;
        height: 1090px;
        top: -791px;
        left: 177px;
        gap: 0px;
        opacity: 0px;
    }
}

.banner-heading {
    width: 574px;
    height: 112px;
    top: 243px;
    left: 120px;
    font-family: "Roboto";
    size: 440x;
    line-height: 56px;
    color: #FFFFFF;
}

.banner-caption {
    color: #f5f7fa;
    font-family: "Roboto";
    font-size: 24px;
    font-weight: 300;
}

.custom-button {
    color: #ffffff;
    width: fixed(211px);
    height: fixed(52px);
    top: 401px;
    left: 120;
    gap: 4px;
}

.kk-1 {
    width: 7.97px;
    height: 472.31px;
    top: 628.97px;
    left: 120px;
    padding: 2px 0px 0px 0px;
    gap: 2px;
    opacity: 0px;
    angle: 90 deg;
    background: #F27121;

}


.kk-2 {
    width: 7.97px;
    height: 472.31px;
    top: 628.97px;
    left: 120px;
    padding: 2px 0px 0px 0px;
    gap: 2px;
    opacity: 0px;
    angle: 90 deg;
    background: #F27121;
}

.kk-3 {
    width: 7.97px;
    height: 472.31px;
    top: 908.97px;
    left: 120px;
    padding: 2px 0px 0px 0px;
    gap: 2px;
    opacity: 0px;
    angle: 90 deg;
    background: #F27121;
}

.kk-4 {
    width: 7.97px;
    height: 472.31px;
    top: 908.97px;
    left: 120px;
    padding: 2px 0px 0px 0px;
    gap: 2px;
    opacity: 0px;
    angle: 90 deg;
    background: #F27121;
}

.kk-5 {
    width: 7.97px;
    height: Fixed 1, 200px;
    top: 1554.97px;
    left: 120px;
    padding: 2px 0px 0px 0px;
    gap: 2px;
    opacity: 0px;
    angle: 90 deg;
    background: #F27121;

}

.custom-outline-button {
    color: #d0b200;
    background-color: transparent;
    width: 130px;
    height: 45px;
    border-style: solid;
    border-width: 1px;
    border-color: #d0b200;
    border-radius: 8px;
}

.cards-container {
    width: 584px;
    height: 530px;
    top: 963px;
    left: 120px;
    border: 1px;
    color: #CECECE;

}

.card {
    width: 584px;
    height: 530px;
    top: 963px;
    left: 120px;
    border: 1px;
    color: #CECECE;
}

.card-background-container {
    width: 560px;
    height: 434px;
    top: 12px;
    left: 12px;
    color: #FOFOFO;
}

.nike-bg-image-1 {
    background-image: url("https://s3-alpha-sig.figma.com/img/22f6/b7b5/b47561aa2ad560235e2702e286a6d4b7?Expires=1720396800&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=N4RpXidMPsQm7pabNJsO4fatsHc2XZffXb8eFLYsL9exMRLgNBYUbgWUgkb2ljo3OUjWJoq-makvZH7uIRjijNRwhVN4FM~2hp6TTQaoT6qKb6EOif-am~8zGpVTrmDeXWdENqjBUpsOCocAlzNIq8BxxHsIRbzyWGrKTVv6bXtQSXAlIIDviSXybiQg~14rCi3z2kKr~9Hr4B552rizXaX2N6ZA5udDuwQnKcsi0es2K8Q1cIJIEfnkrFXyUY7c4IOgjYnpFH8fkRA-8AD5Wju8UUVGzERkfI1QAHtdvNB0cwamTLa473~dIACN16BiT4-EhE5R0IZXSszuwDMCcQ__");
}

.nike-bg-image-2 {
    background-image: url("https://s3-alpha-sig.figma.com/img/22f6/b7b5/b47561aa2ad560235e2702e286a6d4b7?Expires=1720396800&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=N4RpXidMPsQm7pabNJsO4fatsHc2XZffXb8eFLYsL9exMRLgNBYUbgWUgkb2ljo3OUjWJoq-makvZH7uIRjijNRwhVN4FM~2hp6TTQaoT6qKb6EOif-am~8zGpVTrmDeXWdENqjBUpsOCocAlzNIq8BxxHsIRbzyWGrKTVv6bXtQSXAlIIDviSXybiQg~14rCi3z2kKr~9Hr4B552rizXaX2N6ZA5udDuwQnKcsi0es2K8Q1cIJIEfnkrFXyUY7c4IOgjYnpFH8fkRA-8AD5Wju8UUVGzERkfI1QAHtdvNB0cwamTLa473~dIACN16BiT4-EhE5R0IZXSszuwDMCcQ__");
}

.To {
    font-family: "Roboto";
    font-size: 16px;
    font-weight: 400;
    line-height: 32px;
    text-align: center;
    color: #000000;


}

.card-heading-1 {
    font-family: Roboto;
    font-size: 20px;
    font-weight: 600;
    line-height: 28px;
    text-align: left;
    background: #000000;
}

.card-heading-2 {
    width: 146px;
    height: 28px;
    gap: 0px;
    opacity: 0px;
    background: #000000;
}

.custom-button-22 {
    width: Fixed 211px;
    height: Fixed 52px;
    top: 466px;
    left: 361px;
    gap: 4px;
    opacity: 0px;
    background: #FE0000;
}

.custom-button-33 {
    width: Fixed 211px;
    height: Fixed 52px;
    top: 466px;
    left: 361px;
    gap: 4px;
    opacity: 0px;
    background: #FE0000;


}


.foot {
    width: 1441px;
    height: 104px;
    top: 7px;
    gap: 0px;
    opacity: 0px;
    angle: -0 deg;
    background: #25A769;
    background: #ECE14C;
    background: #F27121;
}

.body {
    width: 1441px;
    height: 118px;
    top: 1643px;
    left: -1px;
    gap: 0px;
    opacity: 0px;
}

.heading-44 {
    width: 161px;
    height: 25px;
    top: 25px;
    left: 640px;
    gap: 0px;
    opacity: 0px;

}

.logo-1 {
    width: 36px;
    height: 36px;
    gap: 0px;
    opacity: 0px;
}

.logo-2 {
    width: 36px;
    height: 36px;
    gap: 0px;
    opacity: 0px;
}

.logo-3 {
    width: 36px;
    height: 36px;
    gap: 0px;
    opacity: 0px;
}

.logo-4 {
    width: 36px;
    height: 36px;
    gap: 0px;
    opacity: 0px;
}

.logo-5 {
    width: 36px;
    height: 36px;
    gap: 0px;
    opacity: 0px;

}








