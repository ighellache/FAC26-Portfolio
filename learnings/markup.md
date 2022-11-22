# Markup portfolio

## 1. Structure a site using semantic HTML to aid accessibility

        <!-- Hero Section -->
        <div class="mainindex">
            <div class="maini__container">
                <div class="maini__content">
                    <h1 class="intro">Hello, my name is Iman</h1>
                    <h2>Welcome to my page</h2>
                    <p>This is where I showcase my work</p>
                    <button class="maini__btn"><a href="/commentbox.html">Click here to leave a review</a></button>
                </div>
                <div class="maini_img--container">
                    <img src="/images/moi.jpeg" alt="pic" id="maini__img">
                </div>
            </div>
        </div>

Source: https://github.com/ighellache/ighellache.github.io
## 2. Make a web page more readable for screen readers
:root {
    --purple: #80558C;
    --white: #FFF;
    --grey: #5b5b5b;
    --yellow: #e9c93a;

    --text-size: 18px;
    --h1-size: 36px;
    --h2-size: 28px;
    --h3-size: 26px;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body {
    width: 100vw;
    height: 100vh;
    padding-top: 100px;
}

![image](https://user-images.githubusercontent.com/78818760/203399358-75ee4aa7-8c41-411a-8913-119368ae84b1.png)

Source: https://github.com/fac26/thepurpleelephant
## 3. Design a UI without relying solely on colour, so that we don’t exclude colour-blind users
body {
    height: 100vh;
    background: black;
}
.container {
    width: 40%;
    min-width: 450px;
    position: absolute;
    transform: translate(-50%,-50%);
    top: 50%;
    left: 50%;
    background: white;
}

![image](https://user-images.githubusercontent.com/78818760/203399105-8c25570c-657b-4397-af25-8197a738bc18.png)

Source: https://github.com/fac26/Iman-Dominic.L-Testing
## 4. Ensure our UI has sufficient colour contrast so that everyone can perceive it comfortably
body {
    height: 100vh;
    background: black;
}
.container {
    width: 40%;
    min-width: 450px;
    position: absolute;
    transform: translate(-50%,-50%);
    top: 50%;
    left: 50%;
    background: white;
}

![image](https://user-images.githubusercontent.com/78818760/203399105-8c25570c-657b-4397-af25-8197a738bc18.png)

Source: https://github.com/fac26/Iman-Dominic.L-Testing

## 5. Use various tools to check that a website meets accessibility criteria

![image](https://user-images.githubusercontent.com/78818760/203401405-a4b49312-194d-4a9b-a8c2-ecf32ab18933.png)

Also using semantic HTML for accessibility: clear comments, clear class names(maini is main-index)etc.
   <!-- Hero Section -->
        <div class="mainindex">
            <div class="maini__container">
                <div class="maini__content">
                    <h1 class="intro">Hello, my name is Iman</h1>
                    <h2>Welcome to my page</h2>
                    <p>This is where I showcase my work</p>
                    <button class="maini__btn"><a href="/commentbox.html">Click here to leave a review</a></button>
                </div>
                <div class="maini_img--container">
                    <img src="/images/moi.jpeg" alt="pic" id="maini__img">
                </div>
            </div>
        </div>
Source: Right click on page -> inspect -> click on >> -> select Lighthouse and click analyze page load

## 6. Ensure a website displays well on screens of different sizes
<meta name="viewport" content="width=device-width, initial-scale=1.0">

@media all and (max-width: 850px) {
    .toggle-navbar {
        display: flex
    }

    .header {
        flex-direction: column;
        align-items: flex-start;
    }
    nav {
        width: 100%;
    }    
    .navbar {
        flex-direction: column;
        display: none;
    }
    .navbar-ctn ul li {
        text-align: center;
        width: 100%;
    }
    .navbar.active {
        display: flex;
    }
}

Source: https://github.com/fac26/thepurpleelephant

## 7. Use CSS media queries to ensure content is always presented effectively

@media all and (max-width: 850px) {
    .toggle-navbar {
        display: flex
    }

    .header {
        flex-direction: column;
        align-items: flex-start;
    }
    nav {
        width: 100%;
    }    
    .navbar {
        flex-direction: column;
        display: none;
    }
    .navbar-ctn ul li {
        text-align: center;
        width: 100%;
    }
    .navbar.active {
        display: flex;
    }
}

Source: https://github.com/fac26/thepurpleelephant

## 8. Demonstrate a mobile-first approach to designing a website with a great user experience


## 9. Create an attractive and accessible colour palette for a project

:root {
    --purple: #80558C;
    --white: #FFF;
    --grey: #7C7C7C;
    --yellow: #e9c93a;
    
Source: https://github.com/fac26/thepurpleelephant
## 10. Use CSS variables to apply repeated colours to HTML elements
:root {
    --purple: #80558C;
    --white: #FFF;
    --grey: #7C7C7C;
    --yellow: #e9c93a;
    
Source: https://github.com/fac26/thepurpleelephant
