
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travel Website Structure</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
      body {
        font-family: 'Inter', sans-serif;
      }
    </style>
</head>
<body class="bg-gray-100">
    <header class="bg-blue-500 text-white py-4 flex justify-between items-center shadow-md sticky top-0 z-10 rounded-md">
        <div class="logo text-xl font-bold ml-4">   RWANDA-TOURS</div>
        <nav class="mr-4">
            <ul class="flex space-x-4">
                <li><a href="#" class="hover:text-blue-300 no-underline">Home</a></li>
                <li><a href="#" class="hover:text-blue-300 no-underline">About</a></li>
                <li><a href="#" class="hover:text-blue-300 no-underline">Our Tours</a></li>
                <li><a href="#" class="hover:text-blue-300 no-underline">Services</a></li>
                <li><a href="#" class="hover:text-blue-300 no-underline">Blog</a></li>
                <li><a href="#" class="hover:text-blue-300 no-underline">Contact Us</a></li>
                 <li><a href="#" class="hover:text-blue-300 no-underline">Login / Sign Up</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero-section bg-cover bg-center text-white py-20" style="background-image: url('./crater lake mountain.jpg');">
        <div class="container mx-auto text-center">
            <h1 class="text-4xl font-bold mb-4">VISIT RWANDA</h1>
            <p class="text-lg mb-8">SAID TO BE THE LAND OF A THOUSAND HILLS</p>
            <p class="text-base mb-8">ALL YOU HAVE TO DO IS CHOOSE WHAT YOU LIKE AND WE WILL DO THE REST</p>
            <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-3 px-6 rounded-full" ><a href="View All Travels.html">view all Travels</a></button>
        </div>
    </section>

    <section class="tour-section py-16 bg-gray-100">
        <div class="container mx-auto text-center">
            <h2 class="text-2xl font-bold mb-4 text-gray-800">Find a Tour By Destination</h2>
             <p class="text-base mb-8 text-gray-600">think about it, why choose one when you can simply explorer everything</p>
            <div class="flex justify-center space-x-4">
                <div class="destination-card bg-white rounded-lg shadow-md overflow-hidden w-64">
                    <img src="https://placehold.co/400x300/EEE/AAA?text=PARKS&font=Montserrat" alt="Parks" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2 text-gray-800">Parks</h3>
                        <p class="text-gray-600 text-sm mb-4">explorer the parks of the Rwanda.</p>
                        <a href="parks.html" class="text-blue-500 hover:text-blue-700 font-bold">CHOOSE</a>
                    </div>
                </div>
                <div class="destination-card bg-white rounded-lg shadow-md overflow-hidden w-64">
                    <img src="https://placehold.co/400x300/EEE/AAA?text=culture&font=Montserrat" alt="culture" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2 text-gray-800">Rwandan culture</h3>
                        <p class="text-gray-600 text-sm mb-4">explorer the culture of Rwanda</p>
                        <a href="#" class="text-blue-500 hover:text-blue-700 font-bold">CHOOSE</a>
                    </div>
                </div>
                <div class="destination-card bg-white rounded-lg shadow-md overflow-hidden w-64">
                    <img src="https://placehold.co/400x300/EEE/AAA?text=ACCOMODATION&font=Montserrat" alt="ACCOMODATION" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2 text-gray-800">Accomodation</h3>
                        <p class="text-gray-600 text-sm mb-4">choose where to live and let us book it.</p>
                        <a href="#" class="text-blue-500 hover:text-blue-700 font-bold">CHOOSE</a>
                    </div>
                </div>
                 <div class="destination-card bg-white rounded-lg shadow-md overflow-hidden w-64">
                    <img src="https://placehold.co/400x300/EEE/AAA?text=TRANSPORT&font=Montserrat" alt="TRANSPORT" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2 text-gray-800">TRANSPORT</h3>
                        <p class="text-gray-600 text-sm mb-4">Chooose how you will be going from place to place.</p>
                        <a href="#" class="text-blue-500 hover:text-blue-700 font-bold">CHOOSE</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-gray-800 text-white py-4 text-center rounded-md">
        <p>© visit rwanda through RWANDA-TOURS</p>
    </footer>
</body>
</html>
