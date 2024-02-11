<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OTP Verifaction</title>
    <link rel="stylesheet" href="style.css"/>
</head>
<body>
    <div class="container">
        <h4>Enter Your 4 digit OTP</h4>

        <form class="form">
            <div class="input_firld_box">
                <input type="number"/>
                <input type="number" disabled />
                <input type="number" disabled />
                <input type="number" disabled />
            </div>

            <button>verify OTP</button>
        </form>
    </div>
    
    
</body>
      <script src="script.js"></script>
</html>

<STyle>
    @import url("https://fonts.google.com/?display=swap");

    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: "inter" , sans-serif ;
    }
    body {
        min-height: 100vh;
        display: flex;
        align-items: center;
        justify-content: center;
        background: #e0e0e0;
    }

    .container{
        width: 300px;
        height: auto;
        padding: 480px 30px;
        background-color: white;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        border-radius: 15px;
    }

    h4{
        font-size: 20px;
        color: #121212;

    }

    .input_field_box input:focus{
        outline: 1.5px solid #00b991;
        outline-offset: 2px;
    }
    form button {
        margin-top: 25px;
        width: 92%;
        color: #525252;
        font-size: 16px;
        padding: 10px 0;
        font-weight: 600;
        border-radius: 6px;
        pointer-events: none;
        cursor: pointer;
        background: #e9d585;
        transition: all 0.2s ease;

    }
    form button.active{
        background: #ffcc00;
        pointer-events: auto;
        color: #000000;

    }
    form button:hover {
        background: #e6b801;
    }
    .form{
        width: 100%;
         height: auto;
         display: flex;
         flex-direction: column;
         align-items: center;
         padding-top: 20px;

    }

    .input_field_box{
        width: 100%;
        height: auto;
        display: flex;
        flex-direction: row;
        justify-content: space-evenly;
    }
    .input_field_box input{
        border: none;
        max-width: 20%;
         height: 60px;
         text-align: center;
         border-radius: 5px;
         background: #f0f0f0;
         font-size: 25px;
    }

    .input_field_box input::webkit-inner-spin-bitton,
    .input_field_box input::webkit-outer-spin-button{
        display: none;
    }
    .form{
        width: 100%;
        height: auto;
        display: flex;
        flex-direction: column;
        align-items: center;
        padding-top: 20px;
    }

    input_field_box{
        width: 100%;
        height: auto;
        display: flex;
        flex-direction: row;
        justify-content: space-evenly;
    }

    .input_field_box input{
        border: none;
        max-width: 20%;
        height: 60px;
        text-align: center;
        border-radius: 5px;
        background: #f0f0f0;
        font-size: 25px;
    }
    .input_field_box input::-webkit-inner-spin-button,
    .input_field_box input::-webkit-inner-spin-button{
        display: none;
    }

</STyle>
