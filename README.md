# Arpit-web<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login Form</title>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/2.2.19/tailwind.min.css" >
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700;900&display=swap" >
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.2.0/remixicon.css">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
    }
  </style>
</head>
<body class="m-0 p-0 box-border">
  <section class="w-full h-screen bg-cover bg-center flex items-center justify-center"
   style="background-image: linear-gradient(rgba(0,0,0,.2),rgba(0,0,0,.2)), url('https://img.freepik.com/free-vector/geometric-network-connection-background_23-2148876717.jpg?t=st=1721308476~exp=1721312076~hmac=bf8f326944a0fd24651b357d1583364d942664976f21d1d13736c602db1fc39c&w=1060');">
    <form action="index.html" class="w-80 bg-white bg-opacity-20 p-6 rounded-md flex 
    flex-col items-center justify-center backdrop-blur-sm">
      <h1 class="text-white">Login</h1>
      <div class="w-full relative mt-4">
        <input type="text" placeholder="Username" required class="w-full bg-transparent
         border border-white rounded-full outline-none text-white text-base py-2 px-3">
        <i class="ri-user-fill absolute right-6 top-1/2 transform -translate-y-1/2
         text-white"></i>
      </div>
      <div class="w-full relative mt-4">
        <input type="password" placeholder="Password" required class="w-full bg-transparent
         border border-white rounded-full outline-none text-white text-base py-2 px-3">
        <i class="ri-lock-fill absolute right-6 top-1/2 transform -translate-y-1/2 text-white"></i>
      </div>
      <div class="w-full flex justify-between text-white mt-4">
        <label class="flex items-center"><input type="checkbox" class="mr-2">Remember Me</label>
        <a href="#" class="text-white transition duration-300 hover:underline">Forgot Password</a>
      </div>
      <button class="bg-white font-semibold text-base py-2 px-5 w-2/5 outline-none border-none
       rounded-full mt-4 mb-4">Login</button>
      <p class="text-white">Don't have an account? <a href="#" class="text-white
         transition duration-300 hover:underline">Register</a></p>
    </form>
  </section>
</body>
</html>
