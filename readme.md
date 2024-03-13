<h1 align="center">Welcome to Bitbarg Project 👋</h1>

# Bitbarg Project

In this project, we designed the Bitberg site, which is one of the famous Iranian sites for online exchange

## Skills

We use html css javascript in this project

## Usage

For the JavaScript part, we first define a function that actually increases the price by increasing the number

```javascript
var btn_price=1538270496;

document.getElementById("price").value=btn_price.toLocaleString();

function mohasebe(){
    let tedad=  document.getElementById("tedad").value;
    document.getElementById("price").value = (tedad * btn_price).toLocaleString();
}
```

In the following, we defined a function for the site menu, which by clicking on each section, it finds a different style and the content of each section changes.

```javascript
function filedset_border(fs){

    document.getElementById("fset1").style.borderColor='#c2c2c2';
    document.getElementById("fset1").style.borderWidth='1px';

    document.getElementById("fset2").style.borderColor='#c2c2c2';
    document.getElementById("fset2").style.borderWidth='1px';

    document.getElementById("fset3").style.borderColor='#c2c2c2';
    document.getElementById("fset3").style.borderWidth='1px';

    

    if (fs==1){
    document.getElementById("fset1").style.borderColor='#4285F2';
    document.getElementById("fset1").style.borderWidth='2px';
    }

    
    if (fs==2){
    document.getElementById("fset2").style.borderColor='#4285F2';
    document.getElementById("fset2").style.borderWidth='2px';
    }


    
    if (fs==3){
    document.getElementById("fset3").style.borderColor='#4285F2';
    document.getElementById("fset3").style.borderWidth='2px';
    }
}

function btns(bt){


    document.getElementById("btn1").removeAttribute("class");
    document.getElementById("btn1").setAttribute("class","btn2");
    document.getElementById("btn2").removeAttribute("class");
    document.getElementById("btn2").setAttribute("class","btn2");
    document.getElementById("btn3").removeAttribute("class");
    document.getElementById("btn3").setAttribute("class","btn2");


    if (bt==1){
        document.getElementById("btn1").removeAttribute("class");
        document.getElementById("btn1").setAttribute("class","btn1");
        document.getElementById("btn_kharid").innerText="خرید ارز";
        btn_price=1538270496;
        document.getElementById("price").value=btn_price.toLocaleString();
    }

    if (bt==2){
        document.getElementById("btn2").removeAttribute("class");
        document.getElementById("btn2").setAttribute("class","btn1");
        document.getElementById("btn_kharid").innerText="فروش ارز";
        btn_price=1522905086;
        document.getElementById("price").value=btn_price.toLocaleString();
    }

    if (bt==3){
        document.getElementById("btn3").removeAttribute("class");
        document.getElementById("btn3").setAttribute("class","btn1");
    }
}
```


## Result

This project was written by Majid Tajanjari and the Aiolearn team, and we need your support!❤️

# پروژه بیت برگ

در این پروژه سایت بیت برگ که یکی از سایت های معروف ایرانی برای تبادل آنلاین است را طراحی کردیم

## مهارت ها

ما در این پروژه از html css javascript استفاده می کنیم

## نحوه استفاده

برای قسمت جاوا اسکریپت، ابتدا تابعی را تعریف می کنیم که در واقع با افزایش تعداد، قیمت را افزایش می دهد

```javascript
var btn_price=1538270496;

document.getElementById("price").value=btn_price.toLocaleString();

function mohasebe(){
    let tedad=  document.getElementById("tedad").value;
    document.getElementById("price").value = (tedad * btn_price).toLocaleString();
}
```

در ادامه یک تابع برای منوی سایت تعریف کردیم که با کلیک بر روی هر قسمت استایل متفاوتی پیدا می کند و محتوای هر قسمت تغییر می کند.

```javascript
function filedset_border(fs){

    document.getElementById("fset1").style.borderColor='#c2c2c2';
    document.getElementById("fset1").style.borderWidth='1px';

    document.getElementById("fset2").style.borderColor='#c2c2c2';
    document.getElementById("fset2").style.borderWidth='1px';

    document.getElementById("fset3").style.borderColor='#c2c2c2';
    document.getElementById("fset3").style.borderWidth='1px';

    

    if (fs==1){
    document.getElementById("fset1").style.borderColor='#4285F2';
    document.getElementById("fset1").style.borderWidth='2px';
    }

    
    if (fs==2){
    document.getElementById("fset2").style.borderColor='#4285F2';
    document.getElementById("fset2").style.borderWidth='2px';
    }


    
    if (fs==3){
    document.getElementById("fset3").style.borderColor='#4285F2';
    document.getElementById("fset3").style.borderWidth='2px';
    }
}

function btns(bt){


    document.getElementById("btn1").removeAttribute("class");
    document.getElementById("btn1").setAttribute("class","btn2");
    document.getElementById("btn2").removeAttribute("class");
    document.getElementById("btn2").setAttribute("class","btn2");
    document.getElementById("btn3").removeAttribute("class");
    document.getElementById("btn3").setAttribute("class","btn2");


    if (bt==1){
        document.getElementById("btn1").removeAttribute("class");
        document.getElementById("btn1").setAttribute("class","btn1");
        document.getElementById("btn_kharid").innerText="خرید ارز";
        btn_price=1538270496;
        document.getElementById("price").value=btn_price.toLocaleString();
    }

    if (bt==2){
        document.getElementById("btn2").removeAttribute("class");
        document.getElementById("btn2").setAttribute("class","btn1");
        document.getElementById("btn_kharid").innerText="فروش ارز";
        btn_price=1522905086;
        document.getElementById("price").value=btn_price.toLocaleString();
    }

    if (bt==3){
        document.getElementById("btn3").removeAttribute("class");
        document.getElementById("btn3").setAttribute("class","btn1");
    }
}
```


## نتیجه

این پروژه توسط مجید تجن جاری و تیم Aiolearn نوشته شده است و ما به حمایت شما نیازمندیم!❤️