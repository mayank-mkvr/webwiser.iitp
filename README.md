# YankHub - Your Ultimate Game Store

Ever tried scrolling through endless online stores just to find that one game you're itching to play? Yeah, me too. That's why I built YankHub. Think of it as your go-to digital shelf for all things gaming. We're talking curated selections, quick browsing, and zero fluff. Basically, it's like having a well-organized gaming library at your fingertips, where you can "yank" your favorite games instantly.


Imagine you're prepping for a weekend gaming marathon. You don't want to waste time sifting through cluttered marketplaces. YankHub gives you a clean, focused view of the latest titles and deals, letting you jump right into the action.

## Installation & Usage

1.  **Clone the Repo:** `git clone [webwiser.iitp](https://github.com/mayank-mkvr/webwiser.iitp.git)`
2.  **Open `index.html`:** Just open the `index.html` file in your favorite browser.
3.  **Explore:** Navigate through the intuitive interface to check out the games.

## Technologies Used

* HTML
* CSS
* RemixIcon
* Google Fonts (Inter)

## Key Features

* Clean and intuitive user interface.
* Showcase of popular games with details (category, platform, price).
* Simple navigation for easy browsing.
* Animated logo and button for a dynamic feel.
* Horizontal scrolling for product navigation.

## Additional Notes

* This project focuses on the front-end design. Future iterations might include backend integration for a fully functional e-commerce platform.
* This project is designed to be a simple and fast game store display.
* Deployed version : (https://inspiring-tulumba-3b445e.netlify.app/)]



**index.html**

[Uploading<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>YankHub - Your Ultimate Game Store</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap" rel="stylesheet">
<link
    href="https://cdn.jsdelivr.net/npm/remixicon@4.5.0/fonts/remixicon.css"
    rel="stylesheet"
/>
<link rel="stylesheet" href="style.css">
<link rel="stylesheet" href="animation.css">
</head>
<body>
    <div class="main">
        <div class="nav">
            <div class="nav-part-1">
                <img src="images/Yank logo.png" alt="logo">
                <ul>
                    <li>Home</li>
                    <li>XBOX</li>
                    <li>Playstation</li>
                    <li>Accessories</li>
                    <li>Pre-Order</li>
                </ul>
            </div>
            <div class="nav-part-2">
                <i class="ri-search-eye-line"></i>
                <i class="ri-shopping-cart-fill"></i>
                <i class="ri-menu-line"></i>
            </div>
        </div>
        <div class="content">
            <div class="content-left">
                <h5> Level Up Your Game </h5>
                <h1> Yank Limited Edition </h1>
                <p> Discover the latest titles and exclusive deals at YankHub.
                </p>
                <button class="btn"> Shop Now </button>
            </div>
            <div class="content-right">
                <div class="product">
                    <img src="images/Wukong game.jpg" alt="wukong">
                    <h4>Black Myth Wukong</h4>
                    <p class="category"> Deluxe Edition</p>
                    <p class="platform"> PS5 </p>
                    <p class="price"> Rs 5499 </p>
                </div>
                <div class="product">
                    <img src="images/godofwar.jpg" alt="wukong">
                    <h4>God Of War</h4>
                    <p class="category"> Standard</p>
                    <p class="platform"> PS4 </p>
                    <p class="price"> Rs 3999 </p>
                </div>
                <div class="product">
                    <img src="images/Assassin Cred.jpg" alt="wukong">
                    <h4>Assassin's Cred Shadow</h4>
                    <p class="category"> Special Edition</p>
                    <p class="platform"> Xbox </p>
                    <p class="price"> Rs 4999</p>
                </div>
                <div class="product">
                    <img src="images/starwars.jpg" alt="wukong">
                    <h4>Starwar Outlaws </h4>
                    <p class="category"> Gold Edition</p>
                    <p class="platform"> Xbox </p>
                    <p class="price"> Rs 7999</p>
                </div>
                <div class="product">
                    <img src="images/call of duty.jpg" alt="wukong">
                    <h4>Call of Duty </h4>
                    <p class="category"> Standard</p>
                    <p class="platform"> PS5 </p>
                    <p class="price"> Rs 4999</p>
                </div>
            </div>
        </div>
    </div>
    
</body>
</html>

**style.css**

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
html,body{
    font-family: "Inter", serif;
    font-weight: 400;
}
.main{
    height: 100vh;
    width: 100%;
    background-color: #d0d4D5;
}
.nav{
    height: 100px;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 50px;
}
.nav-part-1{
    display: flex;
    align-items: center;
    justify-content: center;

}
.nav-part-1 ul{
    display: flex;
    justify-content: center;
    list-style: none;
}
.nav-part-1 ul li{
    margin-right: 40px;
    font-size: 19px;
    font-weight: 500;
    text-transform: uppercase;
    cursor: pointer;

}
.nav img{
    height: 80px;
    width: auto;
    margin-right: 60px;
    cursor: pointer;
    
}

/* Stylling for nav part 2 */
.nav-part-2 i{
    margin-right: 40px;
    font-size: 21px;
    font-weight: 500;
    cursor: pointer;

}
.content{
    height: calc(100% - 110px);
    width: 100%;
    position: relative;
    display: flex;
}
.content-left{
    height: 100%;
    width: 40%;
    padding: 80px 100px;
}
.content-left h5{
    font-size: 20px;
    text-transform: capitalize;
    color: #555;
    margin-bottom: 10px;
}
.content-left h1{
    text-transform: uppercase;
    color: black;
    margin-bottom: 25px;
    font-size: 55px;
}
.content-left p{
    font-size: 20px;
    color: #000;
    width: 80%;
    margin-bottom: 30px;
}
.btn{
    background-color: #000;
    color: white;
    font-size: 15px;
    padding: 12px 40px;
    font-weight: 600;
    border: none;
    border-radius: 50;
    border-top-left-radius: 0;
}
/* Styling right side content */
.content-right{
    height: 100%;
    width: 60%;
    padding: 110px 100px;
    white-space: nowrap;
    overflow-x: auto;
}
.content-right::-webkit-scrollbar{
    display: none;
}
.product{
    height: 370px;
    width: 250px;
    background-color: #1011;
    position: relative;
    box-shadow: 0 5px 10px rgba(17, 0, 17, 0.3);
    display: inline-block;
    margin-right: 20px;
}
.product img{
    height: 100%;
    width: 100%;
    object-fit: contain;
    position: absolute;
    bottom: 20%;
}
.product h4{
    font-size: 18px;
    text-transform: capitalize;
    position: absolute;
    bottom: 22%;
    text-align: center;
    justify-content: center;
}
.category{
    position: absolute;
    bottom: 17%;
    font-weight: 500;
    text-transform: capitalize;
}
.platform{
    position: absolute;
    bottom: 12%;
    font-weight: 500;
    text-transform: capitalize;
}
.price{
    font-size: 16px;
    position: absolute;
    bottom: 5%;
    font-weight: 500;
    text-transform: capitalize;
}

**animation.css**

/* General Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
html, body {
    font-family: "Inter", serif;
    font-weight: 400;
    overflow-x: hidden;
}
.main {
    height: 100vh;
    width: 100%;
    background-color: #d0d4D5;
}

/* Navbar */
.nav {
    height: 100px;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 50px;
    animation: slideDown 1s ease-in-out;
}
.nav-part-1 {
    display: flex;
    align-items: center;
    justify-content: center;
}
.nav-part-1 ul {
    display: flex;
    justify-content: center;
    list-style: none;
}
.nav-part-1 ul li {
    margin-right: 40px;
    font-size: 19px;
    font-weight: 500;
    text-transform: uppercase;
    cursor: pointer;
    transition: color 0.3s ease-in-out;
}
.nav-part-1 ul li:hover {
    color: #ff4500;
}

.nav img {
    height: 80px;
    width: auto;
    margin-right: 60px;
    cursor: pointer;
    animation: rotateLogo 5s linear infinite;
}

.nav-part-2 i {
    margin-right: 40px;
    font-size: 21px;
    font-weight: 500;
    cursor: pointer;
    transition: transform 0.3s ease-in-out;
}
.nav-part-2 i:hover {
    transform: scale(1.2);
}

/* Shop Now Button Animation */
.btn {
    background-color: #000;
    color: white;
    font-size: 15px;
    padding: 12px 40px;
    font-weight: 600;
    border: none;
    border-radius: 5px;
    border-top-left-radius: 0;
    transition: background 0.3s ease-in-out, transform 0.3s ease-in-out;
}
.btn:hover {
    background-color: #ff4500;
    transform: scale(1.1);
}

/* Animations */
@keyframes rotateLogo {
    from {
        transform: rotate(0deg);
    }
    to {
        transform: rotate(360deg);
    }
}

@keyframes slideDown {
    from {
        transform: translateY(-50px);
        opacity: 0;
    }
    to {
        transform: translateY(0);
        opacity: 1;
    }
}
 index.html…]()

**ASSESTS :-**



![call of duty](https://github.com/user-attachments/assets/0480c0da-2831-43f8-ad51-787c682c47aa)
![Assassin Cred](https://github.com/user-attachments/assets/23fd32b2-07dc-4d00-a9f6-df64f2549047)
![Yank logo](https://github.com/user-attachments/assets/2262f786-d73d-4a68-b856-1cb3a58e7711)
![Wukong game](https://github.com/user-attachments/assets/6af52b80-8cdd-4b8d-b74b-677eb76d50f8)
![starwars](https://github.com/user-attachments/assets/66dfd0ce-1cbc-4c3b-a466-262f26d5ea5e)
![MARIO](https://github.com/user-attachments/assets/8bb137aa-92e6-4b19-a657-8a416f77e41d)
![godofwar](https://github.com/user-attachments/assets/0192fc7b-7972-4e95-9895-76cbc4765315)
