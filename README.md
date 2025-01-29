<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog writing</title>
    <style>
    
        h1{
            text-align: left;
            font-size: larger;
        }
        h2{
text-align: left;
        }
        img{
            display: block;
            margin: 0 auto;
            padding: 50px;
            border-radius: 24px;
        }

button{
    background-color: white;
    display: block;
    margin: 0 auto;
    color: black;
    padding: 24px;
            border-radius: 5px;
            box-shadow: 12px 1px 15px rgba(0 0 0 0) 0.7;
            transition: all 150ms ease-in-out;
}
button:hover{
            opacity: 0.5;
            cursor: pointer;
        }
footer{
            margin: 15px 0 0 10px;
            text-align: center;
        }
        body{
            background-color: antiquewhite;
        }
    </style>
</head>
<body>
        <h1>Blog writing</h1>
        <h2><strong>Write from home, Remote working just for you</strong></h2>
        <img src="20230328_104833_0000.png"
         alt="Blog writing" 
         width="300px">
    <p>A blog is an online journal or informational website run by an individual, group, or corporation that offers regularly updated content (blog post) about a topic. It presents information in reverse chronological order and it is written in an informal or conversational style. Many organizations and businesses use blogs as part of their content marketing strategies to boost brand awareness and increase conversions. You also can do that in the convience of your home. 
</p>
    <p>Contact us today and get started.</p>
    <button class="me">Contact Us</button>
    <footer><a href="">About Me</a></footer>
</body>
<script>
    function me() {
        let name = prompt("What is your name?");
        let email = prompt("What is your email?");
        alert("Thank you," + name + " We would be in touch with you soon😊");}

    let tapMe = document.querySelector (".me");
   tapMe.addEventListener("click", me)
</script>
</html>
