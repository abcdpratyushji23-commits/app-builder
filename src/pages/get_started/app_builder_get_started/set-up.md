<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Desert Car Drive</title>
<style>
  body {
    margin: 0;
    overflow: hidden;
    background: linear-gradient(skyblue 60%, sandybrown 40%);
    font-family: sans-serif;
  }

  #game {
    position: relative;
    width: 400px;
    height: 600px;
    background: #444;
    margin: 20px auto;
    overflow: hidden;
    border-radius: 10px;
    box-shadow: 0 0 10px #000;
  }

  .road-line {
    position: absolute;
    width: 10px;
    height: 60px;
    background: white;
    left: 195px;
    animation: moveLine 1.2s linear infinite;
  }

  @keyframes moveLine {
    from { top: -60px; }
    to { top: 600px; }
  }

  #car {
    position: absolute;
    bottom: 50px;
    left: 170px;
    width: 60px;
    height: 100px;
    background-image: url('https://cdn-icons-png.flaticon.com/512/744/744465.png');
    background-size: cover;
    background-repeat: no-repeat;
  }

  .tree {
    position: absolute;
    width: 40px;
    height: 80
