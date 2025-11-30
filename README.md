<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Flipkart Style UI</title>
<style>
    body{
        margin:0;
        font-family:sans-serif;
        background:#f3f3f3;
    }
    /* Top Blue Header */
    .header{
        background:#2874F0;
        color:#fff;
        padding:12px;
        display:flex;
        align-items:center;
        gap:10px;
    }
    .header img{
        height:26px;
    }

    /* Search Bar */
    .search{
        padding:10px;
        background:#fff;
    }
    .search input{
        width:100%;
        padding:10px;
        font-size:16px;
        border:1px solid #ccc;
        border-radius:5px;
    }

    /* Categories */
    .categories{
        display:flex;
        overflow-x:auto;
        background:#fff;
        padding:10px 0;
        gap:15px;
    }
    .cat-item{
        text-align:center;
        min-width:70px;
        font-size:14px;
    }
    .cat-item img{
        width:50px;
        height:50px;
        border-radius:50%;
    }

    /* Banner */
    .banner img{
        width:100%;
        margin-top:10px;
    }

    /* Deals Heading */
    .deal-title{
        text-align:center;
        margin-top:10px;
        font-size:20px;
        font-weight:600;
    }
    .timer{
        text-align:center;
        font-size:18px;
        color:red;
        margin-bottom:10px;
    }

    /* Product Cards */
    .products{
        display:grid;
        grid-template-columns:1fr 1fr;
        gap:10px;
        padding:10px;
    }
    .card{
        background:#fff;
        padding:10px;
        border-radius:8px;
    }
    .card img{
        width:100%;
        height:150px;
        object-fit:contain;
    }
    .name{
        font-size:14px;
        margin-top:5px;
    }
</style>
</head>
<body>

<!-- TOP HEADER -->
<div class="header">
    <img src="https://i.ibb.co/7t3nq0J/flipkart-logo.png" alt="">
    <span>Explore Plu
