<h1 align="center">Discord Sales Bot</h1>

<p align="center">It is a very simple system that can be useful for people who perform sales transactions via Discord.</p>

# 

# Installation
In order to install this, you need to run the following command in your respected Command Prompt or Code editor.

```coffeescript
git clone https://github.com/MrRubby/Discord_Sales_Bot.git
```

You can also install by clicking 'Releases' in the tab at the right side.

#

# Getting Started

There are a few settings that you need to adjust for yourself before starting the bot

The code below can be found in ayarlar.json

```js
{
"token": "", // Bot Token
"mongoDB": "", // MongoDB URL
"kategori":"",
"mod":"", // Mod Role ID
"rol1":"", // In order for a discount to be applied to people using the Youtube Join membership
"rol2":"", // The Server Booster role id is for applying a discount to the user who presses boost to the server.
"logKanal":"" // Channel id where the logs will drop
}
```

You can arrange the discount roles according to yourself.

#

# Pay Methods

You can arrange your paying methods according to yourself. It will be enough to browse the files for editing.

#

# How To Use

Its use is quite simple. It will work smoothly if you do the installation correctly.

When adding products to the database, you should leave the urun-kodu field blank. The product code is assigned by the system itself.

Not only that, you can also generate a limited number of promotional codes.

#

# Screenshot

![Screenshot](https://raw.githubusercontent.com/MrRubby/Discord_Sales_Bot/master/Screenshot/urun-ekle.png)

![Screenshot](https://raw.githubusercontent.com/MrRubby/Discord_Sales_Bot/master/Screenshot/urunler.png)

![Screenshot](https://raw.githubusercontent.com/MrRubby/Discord_Sales_Bot/master/Screenshot/urun-bilgi.png)
