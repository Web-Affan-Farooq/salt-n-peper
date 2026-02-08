# salt-n-peper

check this html

```html
    <section class="welcome">
        <h1>Welcome to <span>Salt n Pepper</span> </h1>
        <h1>Resturants ! Our brands</h1>
        <br>
        <p>Please click our brands below for further information, reservations or to order online!
        </p>

        <br><br>

        <div class="welcome-container">
            <div class="card">
                <div class="img-container">
                    <img src="./assets/images/logo.jpg" alt="">
                </div>
                <div>
                    <button type="button" class="btn-lg">
                        Order now
                    </button>
                </div>
            </div>
            <div class="card">
                <div class="img-container">
                    <img src="./assets/images/logo.jpg" alt="">
                </div>
                <div>
                    <button type="button" class="btn-lg">
                        Order now
                    </button>
                </div>
            </div>
            <div class="card">
                <div class="img-container">
                    <img src="./assets/images/logo.jpg" alt="">
                </div>
                <div>
                    <button type="button" class="btn-lg">
                        Order now
                    </button>
                </div>
            </div>
            <div class="card">
                <div class="img-container">
                    <img src="./assets/images/logo.jpg" alt="">
                </div>
                <div>
                    <button type="button" class="btn-lg">
                        Order now
                    </button>
                </div>
            </div>

        </div>
    </section>
```
and also check its css 

```css
.welcome {
    width: 100%;
    text-align: center;
    padding: 70px 0px;

    h1 {
        font-size: 36px;
        line-height: 40px;
        font-weight: lighter;
        font-family: var(--font-opensans);

        span {
            font-family: futurak;
            font-size: 48px;

        }
    }
}

.welcome-container {
    display: grid;
    justify-content: center;
    align-items: center;
    gap: 20px;

    grid-template-columns: repeat(4, 220px);
    width: 100%;

    .card {
        .img-container {
            width: 100%;
            display: flex;
            height: 140px;
            border-radius: 7px;

            img {
                object-fit: contain;
                width: 100%;
                height: 100%;
            }
        }

        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        gap: 10px;
    }
}

@media (max-width:960px) {
    .welcome-container {
        display: block;
        white-space: no-wrap;


        .card {
            display: inline-block;
            white-space: wrap;
        }
    }
}
```

make it responsive and only provide me code