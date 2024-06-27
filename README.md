# rajeswari-sanapathi.product-landing-page-development
#created a captivating product landing page ussing html and css
<!DOCTYPE html>
<html>
<head>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
    <style>
        body{ background-image:url("bg.jpg") ;
                background-position:calc();
                background-repeat: no-repeat;
                background-size:cover;
                background-attachment:scroll;
                
                
    }


        .dropdown-menu {
            max-height: 600px; /* Set the maximum height for the dropdown */
            overflow-y: auto; /* Enable vertical scrolling */
        

                
            overflow-x: hidden; /* Prevent horizontal scrolling */
        }
        

        .gradient-bg {
            
            background-color: linear-gradient(to right, rgb(255, 196, 0), blue,rgba(255, 192, 238, 0.707)); ;
        }
        
        .nav-link {
            transform: scale(1.1);
            transition: color 0.3s, background-color 0.3s;
        }
        .nav-link:hover {
            color: white; /* Change the text color on hover */
            background-color: rgba(32, 8, 136, 0.2); /* Change the background color on hover */
            border-radius: 5px; /* Add a slight border radius for rounded corners */
        }
        h2{
            font-style: italic;
            font-family: Georgia, 'Times New Roman', Times, serif;
            font-stretch: extra-expanded;
            font-size: 70px;
            text-align:left;
            color:  linear-gradient(to right, rgb(255, 196, 0), blue,rgba(255, 192, 238, 0.707));
        
        }
        .order-now-btn {
            display: inline-flex;
            align-items: center;
            background-color: #ff9900; /* Button background color */
            color: white; /* Button text color */
            padding: 10px 20px; /* Button padding */
            border: none; /* Remove border */
            border-radius: 5px; /* Rounded corners */
            font-size: 18px; /* Text size */
            text-decoration: none; /* Remove underline */
            transition: background-color 0.3s; /* Smooth transition */
        }

        .order-now-btn:hover {
            background-color: #cc7a00; /* Darker background color on hover */
        }

        .order-now-btn .btn-icon {
            margin-right: 10px; /* Space between icon and text */
        }
        .contact-us-container {
            text-align: center; /* Center align the content */
            margin-top: 50px; /* Margin at the top for spacing */
        }

        .contact-link {
            display: inline-block; /* Display links in a line */
            margin: 0 10px; /* Margin between links */
            text-decoration: none; /* Remove underline */
            color: #333; /* Link color */
            font-size: 18px; /* Font size */
            transition: color 0.3s; /* Smooth color transition on hover */
        }

        .contact-link:hover {
            color: #007bff; /* Change color on hover */
        }

        .contact-link .fa {
            margin-right: 5px; /* Space between icon and text */
        }
            







    </style>
</head>
<body >

    <div class="container fluid gradient-bg">
        <h1 class="text-center">
            DEV'S NATURALS
            <img src="ice.jpeg" style="height: 7%;width: 7%">
        </h1>
    </div>
    <nav class="navbar navbar-expand-lg bg-body ">
        

        <div class="container">
            <a class="navbar-brand" href="#"><i>home</i></a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            CONE
                        </a>
                        <ul class="dropdown-menu">
                            <!-- Adding 50 flavors for each item -->
                            <li><a class="dropdown-item" href="#">Vanilla</a></li>
                            <li><a class="dropdown-item" href="#">Chocolate</a></li>
                            <li><a class="dropdown-item" href="#">Strawberry</a></li>
                            <li><a class="dropdown-item" href="#">Mint Chocolate Chip</a></li>
                            <li><a class="dropdown-item" href="#">Cookies and Cream</a></li>
                            <li><a class="dropdown-item" href="#">Coffee</a></li>
                            <li><a class="dropdown-item" href="#">Pistachio</a></li>
                            <li><a class="dropdown-item" href="#">Chocolate Marshmallow</a></li>
                            <li><a class="dropdown-item" href="#">Hazelnut</a></li>
                            <li><a class="dropdown-item" href="#">Dark Chocolate</a></li>
                            <li><a class="dropdown-item" href="#">Butterscotch</a></li>
                            <li><a class="dropdown-item" href="#">Peanut Butter Cup</a></li>
                            <li><a class="dropdown-item" href="#">Rocky Road</a></li>
                            <li><a class="dropdown-item" href="#">Mango</a></li>
                            <li><a class="dropdown-item" href="#">Lemon</a></li>
                            <li><a class="dropdown-item" href="#">Coconut</a></li>
                            <li><a class="dropdown-item" href="#">Raspberry</a></li>
                            <li><a class="dropdown-item" href="#">Blackberry</a></li>
                            <li><a class="dropdown-item" href="#">Blueberry</a></li>
                            <li><a class="dropdown-item" href="#">Banana</a></li>
                            <li><a class="dropdown-item" href="#">Caramel</a></li>
                            <li><a class="dropdown-item" href="#">Caramel Swirl</a></li>
                            <li><a class="dropdown-item" href="#">Pumpkin</a></li>
                            <li><a class="dropdown-item" href="#">Apple Pie</a></li>
                            <li><a class="dropdown-item" href="#">Chai</a></li>
                            <li><a class="dropdown-item" href="#">Green Tea</a></li>
                            <li><a class="dropdown-item" href="#">Black Tea</a></li>
                            <li><a class="dropdown-item" href="#">Tiramisu</a></li>
                            <li><a class="dropdown-item" href="#">Red Velvet</a></li>
                            <li><a class="dropdown-item" href="#">Birthday Cake</a></li>
                            <li><a class="dropdown-item" href="#">Mocha</a></li>
                            <li><a class="dropdown-item" href="#">Salted Caramel</a></li>
                            <li><a class="dropdown-item" href="#">Maple Walnut</a></li>
                            <li><a class="dropdown-item" href="#">Brownie</a></li>
                            <li><a class="dropdown-item" href="#">Toffee</a></li>
                            <li><a class="dropdown-item" href="#">S'mores</a></li>
                            <li><a class="dropdown-item" href="#">Cinnamon</a></li>
                            <li><a class="dropdown-item" href="#">Matcha</a></li>
                            <li><a class="dropdown-item" href="#">Lavender</a></li>
                            <li><a class="dropdown-item" href="#">Honey</a></li>
                            <li><a class="dropdown-item" href="#">Ginger</a></li>
                            <li><a class="dropdown-item" href="#">Peppermint</a></li>
                            <li><a class="dropdown-item" href="#">Orange Cream</a></li>
                            <li><a class="dropdown-item" href="#">Rum Raisin</a></li>
                            <li><a class="dropdown-item" href="#">Butter Pecan</a></li>
                            <li><a class="dropdown-item" href="#">Neapolitan</a></li>
                            <li><a class="dropdown-item" href="#">Eggnog</a></li>
                            <li><a class="dropdown-item" href="#">Amaretto</a></li>
                        </ul>
                    </li>
                    <!-- Repeat for each menu item -->
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            FAMILY PACKS
                        </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">Vanilla</a></li>
                            <li><a class="dropdown-item" href="#">Chocolate</a></li>
                            <li><a class="dropdown-item" href="#">Strawberry</a></li>
                            <li><a class="dropdown-item" href="#">Mint Chocolate Chip</a></li>
                            <li><a class="dropdown-item" href="#">Cookies and Cream</a></li>
                            <li><a class="dropdown-item" href="#">Coffee</a></li>
                            <li><a class="dropdown-item" href="#">Pistachio</a></li>
                            <li><a class="dropdown-item" href="#">Chocolate Marshmallow</a></li>
                            <li><a class="dropdown-item" href="#">Hazelnut</a></li>
                            <li><a class="dropdown-item" href="#">Dark Chocolate</a></li>
                            <li><a class="dropdown-item" href="#">Butterscotch</a></li>
                            <li><a class="dropdown-item" href="#">Peanut Butter Cup</a></li>
                            <li><a class="dropdown-item" href="#">Rocky Road</a></li>
                            <li><a class="dropdown-item" href="#">Mango</a></li>
                            <li><a class="dropdown-item" href="#">Lemon</a></li>
                            <li><a class="dropdown-item" href="#">Coconut</a></li>
                            <li><a class="dropdown-item" href="#">Raspberry</a></li>
                            <li><a class="dropdown-item" href="#">Blackberry</a></li>
                            <li><a class="dropdown-item" href="#">Blueberry</a></li>
                            <li><a class="dropdown-item" href="#">Banana</a></li>
                            <li><a class="dropdown-item" href="#">Caramel</a></li>
                            <li><a class="dropdown-item" href="#">Caramel Swirl</a></li>
                            <li><a class="dropdown-item" href="#">Pumpkin</a></li>
                            <li><a class="dropdown-item" href="#">Apple Pie</a></li>
                            <li><a class="dropdown-item" href="#">Chai</a></li>
                            <li><a class="dropdown-item" href="#">Green Tea</a></li>
                            <li><a class="dropdown-item" href="#">Black Tea</a></li>
                            <li><a class="dropdown-item" href="#">Tiramisu</a></li>
                            <li><a class="dropdown-item" href="#">Red Velvet</a></li>
                            <li><a class="dropdown-item" href="#">Birthday Cake</a></li>
                            <li><a class="dropdown-item" href="#">Mocha</a></li>
                            <li><a class="dropdown-item" href="#">Salted Caramel</a></li>
                            <li><a class="dropdown-item" href="#">Maple Walnut</a></li>
                            <li><a class="dropdown-item" href="#">Brownie</a></li>
                            <li><a class="dropdown-item" href="#">Toffee</a></li>
                            <li><a class="dropdown-item" href="#">S'mores</a></li>
                            <li><a class="dropdown-item" href="#">Cinnamon</a></li>
                            <li><a class="dropdown-item" href="#">Matcha</a></li>
                            <li><a class="dropdown-item" href="#">Lavender</a></li>
                            <li><a class="dropdown-item" href="#">Honey</a></li>
                            <li><a class="dropdown-item" href="#">Ginger</a></li>
                            <li><a class="dropdown-item" href="#">Peppermint</a></li>
                            <li><a class="dropdown-item" href="#">Orange Cream</a></li>
                            <li><a class="dropdown-item" href="#">Rum Raisin</a></li>
                            <li><a class="dropdown-item" href="#">Butter Pecan</a></li>
                            <li><a class="dropdown-item" href="#">Neapolitan</a></li>
                            <li><a class="dropdown-item" href="#">Eggnog</a></li>
                            <li><a class="dropdown-item" href="#">Amaretto</a></li>
                            <!-- Add the same list of 50 flavors here -->
                            <!-- ... -->
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            BARS
                        </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">Vanilla</a></li>
                            <li><a class="dropdown-item" href="#">Chocolate</a></li>
                            <li><a class="dropdown-item" href="#">Strawberry</a></li>
                            <li><a class="dropdown-item" href="#">Mint Chocolate Chip</a></li>
                            <li><a class="dropdown-item" href="#">Cookies and Cream</a></li>
                            <li><a class="dropdown-item" href="#">Coffee</a></li>
                            <li><a class="dropdown-item" href="#">Pistachio</a></li>
                            <li><a class="dropdown-item" href="#">Chocolate Marshmallow</a></li>
                            <li><a class="dropdown-item" href="#">Hazelnut</a></li>
                            <li><a class="dropdown-item" href="#">Dark Chocolate</a></li>
                            <li><a class="dropdown-item" href="#">Butterscotch</a></li>
                            <li><a class="dropdown-item" href="#">Peanut Butter Cup</a></li>
                            <li><a class="dropdown-item" href="#">Rocky Road</a></li>
                            <li><a class="dropdown-item" href="#">Mango</a></li>
                            <li><a class="dropdown-item" href="#">Lemon</a></li>
                            <li><a class="dropdown-item" href="#">Coconut</a></li>
                            <li><a class="dropdown-item" href="#">Raspberry</a></li>
                            <li><a class="dropdown-item" href="#">Blackberry</a></li>
                            <li><a class="dropdown-item" href="#">Blueberry</a></li>
                            <li><a class="dropdown-item" href="#">Banana</a></li>
                            <li><a class="dropdown-item" href="#">Caramel</a></li>
                            <li><a class="dropdown-item" href="#">Caramel Swirl</a></li>
                            <li><a class="dropdown-item" href="#">Pumpkin</a></li>
                            <li><a class="dropdown-item" href="#">Apple Pie</a></li>
                            <li><a class="dropdown-item" href="#">Chai</a></li>
                            <li><a class="dropdown-item" href="#">Green Tea</a></li>
                            <li><a class="dropdown-item" href="#">Black Tea</a></li>
                            <li><a class="dropdown-item" href="#">Tiramisu</a></li>
                            <li><a class="dropdown-item" href="#">Red Velvet</a></li>
                            <li><a class="dropdown-item" href="#">Birthday Cake</a></li>
                            <li><a class="dropdown-item" href="#">Mocha</a></li>
                            <li><a class="dropdown-item" href="#">Salted Caramel</a></li>
                            <li><a class="dropdown-item" href="#">Maple Walnut</a></li>
                            <li><a class="dropdown-item" href="#">Brownie</a></li>
                            <li><a class="dropdown-item" href="#">Toffee</a></li>
                            <li><a class="dropdown-item" href="#">S'mores</a></li>
                            <li><a class="dropdown-item" href="#">Cinnamon</a></li>
                            <li><a class="dropdown-item" href="#">Matcha</a></li>
                            <li><a class="dropdown-item" href="#">Lavender</a></li>
                            <li><a class="dropdown-item" href="#">Honey</a></li>
                            <li><a class="dropdown-item" href="#">Ginger</a></li>
                            <li><a class="dropdown-item" href="#">Peppermint</a></li>
                            <li><a class="dropdown-item" href="#">Orange Cream</a></li>
                            <li><a class="dropdown-item" href="#">Rum Raisin</a></li>
                            <li><a class="dropdown-item" href="#">Butter Pecan</a></li>
                            <li><a class="dropdown-item" href="#">Neapolitan</a></li>
                            <li><a class="dropdown-item" href="#">Eggnog</a></li>
                            <li><a class="dropdown-item" href="#">Amaretto</a></li>
                            <!-- Add the same list of 50 flavors here -->
                            <!-- ... -->
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            CUPS
                        </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">Vanilla</a></li>
                            <li><a class="dropdown-item" href="#">Chocolate</a></li>
                            <li><a class="dropdown-item" href="#">Strawberry</a></li>
                            <li><a class="dropdown-item" href="#">Mint Chocolate Chip</a></li>
                            <li><a class="dropdown-item" href="#">Cookies and Cream</a></li>
                            <li><a class="dropdown-item" href="#">Coffee</a></li>
                            <li><a class="dropdown-item" href="#">Pistachio</a></li>
                            <li><a class="dropdown-item" href="#">Chocolate Marshmallow</a></li>
                            <li><a class="dropdown-item" href="#">Hazelnut</a></li>
                            <li><a class="dropdown-item" href="#">Dark Chocolate</a></li>
                            <li><a class="dropdown-item" href="#">Butterscotch</a></li>
                            <li><a class="dropdown-item" href="#">Peanut Butter Cup</a></li>
                            <li><a class="dropdown-item" href="#">Rocky Road</a></li>
                            <li><a class="dropdown-item" href="#">Mango</a></li>
                            <li><a class="dropdown-item" href="#">Lemon</a></li>
                            <li><a class="dropdown-item" href="#">Coconut</a></li>
                            <li><a class="dropdown-item" href="#">Raspberry</a></li>
                            <li><a class="dropdown-item" href="#">Blackberry</a></li>
                            <li><a class="dropdown-item" href="#">Blueberry</a></li>
                            <li><a class="dropdown-item" href="#">Banana</a></li>
                            <li><a class="dropdown-item" href="#">Caramel</a></li>
                            <li><a class="dropdown-item" href="#">Caramel Swirl</a></li>
                            <li><a class="dropdown-item" href="#">Pumpkin</a></li>
                            <li><a class="dropdown-item" href="#">Apple Pie</a></li>
                            <li><a class="dropdown-item" href="#">Chai</a></li>
                            <li><a class="dropdown-item" href="#">Green Tea</a></li>
                            <li><a class="dropdown-item" href="#">Black Tea</a></li>
                            <li><a class="dropdown-item" href="#">Tiramisu</a></li>
                            <li><a class="dropdown-item" href="#">Red Velvet</a></li>
                            <li><a class="dropdown-item" href="#">Birthday Cake</a></li>
                            <li><a class="dropdown-item" href="#">Mocha</a></li>
                            <li><a class="dropdown-item" href="#">Salted Caramel</a></li>
                            <li><a class="dropdown-item" href="#">Maple Walnut</a></li>
                            <li><a class="dropdown-item" href="#">Brownie</a></li>
                            <li><a class="dropdown-item" href="#">Toffee</a></li>
                            <li><a class="dropdown-item" href="#">S'mores</a></li>
                            <li><a class="dropdown-item" href="#">Cinnamon</a></li>
                            <li><a class="dropdown-item" href="#">Matcha</a></li>
                            <li><a class="dropdown-item" href="#">Lavender</a></li>
                            <li><a class="dropdown-item" href="#">Honey</a></li>
                            <li><a class="dropdown-item" href="#">Ginger</a></li>
                            <li><a class="dropdown-item" href="#">Peppermint</a></li>
                            <li><a class="dropdown-item" href="#">Orange Cream</a></li>
                            <li><a class="dropdown-item" href="#">Rum Raisin</a></li>
                            <li><a class="dropdown-item" href="#">Butter Pecan</a></li>
                            <li><a class="dropdown-item" href="#">Neapolitan</a></li>
                            <li><a class="dropdown-item" href="#">Eggnog</a></li>
                            <li><a class="dropdown-item" href="#">Amaretto</a></li>
                            <!-- Add the same list of 50 flavors here -->
                            <!-- ... -->
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            TUBS
                        </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">Vanilla</a></li>
                            <li><a class="dropdown-item" href="#">Chocolate</a></li>
                            <li><a class="dropdown-item" href="#">Strawberry</a></li>
                            <li><a class="dropdown-item" href="#">Mint Chocolate Chip</a></li>
                            <li><a class="dropdown-item" href="#">Cookies and Cream</a></li>
                            <li><a class="dropdown-item" href="#">Coffee</a></li>
                            <li><a class="dropdown-item" href="#">Pistachio</a></li>
                            <li><a class="dropdown-item" href="#">Chocolate Marshmallow</a></li>
                            <li><a class="dropdown-item" href="#">Hazelnut</a></li>
                            <li><a class="dropdown-item" href="#">Dark Chocolate</a></li>
                            <li><a class="dropdown-item" href="#">Butterscotch</a></li>
                            <li><a class="dropdown-item" href="#">Peanut Butter Cup</a></li>
                            <li><a class="dropdown-item" href="#">Rocky Road</a></li>
                            <li><a class="dropdown-item" href="#">Mango</a></li>
                            <li><a class="dropdown-item" href="#">Lemon</a></li>
                            <li><a class="dropdown-item" href="#">Coconut</a></li>
                            <li><a class="dropdown-item" href="#">Raspberry</a></li>
                            <li><a class="dropdown-item" href="#">Blackberry</a></li>
                            <li><a class="dropdown-item" href="#">Blueberry</a></li>
                            <li><a class="dropdown-item" href="#">Banana</a></li>
                            <li><a class="dropdown-item" href="#">Caramel</a></li>
                            <li><a class="dropdown-item" href="#">Caramel Swirl</a></li>
                            <li><a class="dropdown-item" href="#">Pumpkin</a></li>
                            <li><a class="dropdown-item" href="#">Apple Pie</a></li>
                            <li><a class="dropdown-item" href="#">Chai</a></li>
                            <li><a class="dropdown-item" href="#">Green Tea</a></li>
                            <li><a class="dropdown-item" href="#">Black Tea</a></li>
                            <li><a class="dropdown-item" href="#">Tiramisu</a></li>
                            <li><a class="dropdown-item" href="#">Red Velvet</a></li>
                            <li><a class="dropdown-item" href="#">Birthday Cake</a></li>
                            <li><a class="dropdown-item" href="#">Mocha</a></li>
                            <li><a class="dropdown-item" href="#">Salted Caramel</a></li>
                            <li><a class="dropdown-item" href="#">Maple Walnut</a></li>
                            <li><a class="dropdown-item" href="#">Brownie</a></li>
                            <li><a class="dropdown-item" href="#">Toffee</a></li>
                            <li><a class="dropdown-item" href="#">S'mores</a></li>
                            <li><a class="dropdown-item" href="#">Cinnamon</a></li>
                            <li><a class="dropdown-item" href="#">Matcha</a></li>
                            <li><a class="dropdown-item" href="#">Lavender</a></li>
                            <li><a class="dropdown-item" href="#">Honey</a></li>
                            <li><a class="dropdown-item" href="#">Ginger</a></li>
                            <li><a class="dropdown-item" href="#">Peppermint</a></li>
                            <li><a class="dropdown-item" href="#">Orange Cream</a></li>
                            <li><a class="dropdown-item" href="#">Rum Raisin</a></li>
                            <li><a class="dropdown-item" href="#">Butter Pecan</a></li>
                            <li><a class="dropdown-item" href="#">Neapolitan</a></li>
                            <li><a class="dropdown-item" href="#">Eggnog</a></li>
                            <li><a class="dropdown-item" href="#">Amaretto</a></li>
                            <!-- Add the same list of 50 flavors here -->
                            <!-- ... -->
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            CAKES
                        </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">Vanilla</a></li>
                            <li><a class="dropdown-item" href="#">Chocolate</a></li>
                            <li><a class="dropdown-item" href="#">Strawberry</a></li>
                            <li><a class="dropdown-item" href="#">Mint Chocolate Chip</a></li>
                            <li><a class="dropdown-item" href="#">Cookies and Cream</a></li>
                            <li><a class="dropdown-item" href="#">Coffee</a></li>
                            <li><a class="dropdown-item" href="#">Pistachio</a></li>
                            <li><a class="dropdown-item" href="#">Chocolate Marshmallow</a></li>
                            <li><a class="dropdown-item" href="#">Hazelnut</a></li>
                            <li><a class="dropdown-item" href="#">Dark Chocolate</a></li>
                            <li><a class="dropdown-item" href="#">Butterscotch</a></li>
                            <li><a class="dropdown-item" href="#">Peanut Butter Cup</a></li>
                            <li><a class="dropdown-item" href="#">Rocky Road</a></li>
                            <li><a class="dropdown-item" href="#">Mango</a></li>
                            <li><a class="dropdown-item" href="#">Lemon</a></li>
                            <li><a class="dropdown-item" href="#">Coconut</a></li>
                            <li><a class="dropdown-item" href="#">Raspberry</a></li>
                            <li><a class="dropdown-item" href="#">Blackberry</a></li>
                            <li><a class="dropdown-item" href="#">Blueberry</a></li>
                            <li><a class="dropdown-item" href="#">Banana</a></li>
                            <li><a class="dropdown-item" href="#">Caramel</a></li>
                            <li><a class="dropdown-item" href="#">Caramel Swirl</a></li>
                            <li><a class="dropdown-item" href="#">Pumpkin</a></li>
                            <li><a class="dropdown-item" href="#">Apple Pie</a></li>
                            <li><a class="dropdown-item" href="#">Chai</a></li>
                            <li><a class="dropdown-item" href="#">Green Tea</a></li>
                            <li><a class="dropdown-item" href="#">Black Tea</a></li>
                            <li><a class="dropdown-item" href="#">Tiramisu</a></li>
                            <li><a class="dropdown-item" href="#">Red Velvet</a></li>
                            <li><a class="dropdown-item" href="#">Birthday Cake</a></li>
                            <li><a class="dropdown-item" href="#">Mocha</a></li>
                            <li><a class="dropdown-item" href="#">Salted Caramel</a></li>
                            <li><a class="dropdown-item" href="#">Maple Walnut</a></li>
                            <li><a class="dropdown-item" href="#">Brownie</a></li>
                            <li><a class="dropdown-item" href="#">Toffee</a></li>
                            <li><a class="dropdown-item" href="#">S'mores</a></li>
                            <li><a class="dropdown-item" href="#">Cinnamon</a></li>
                            <li><a class="dropdown-item" href="#">Matcha</a></li>
                            <li><a class="dropdown-item" href="#">Lavender</a></li>
                            <li><a class="dropdown-item" href="#">Honey</a></li>
                            <li><a class="dropdown-item" href="#">Ginger</a></li>
                            <li><a class="dropdown-item" href="#">Peppermint</a></li>
                            <li><a class="dropdown-item" href="#">Orange Cream</a></li>
                            <li><a class="dropdown-item" href="#">Rum Raisin</a></li>
                            <li><a class="dropdown-item" href="#">Butter Pecan</a></li>
                            <li><a class="dropdown-item" href="#">Neapolitan</a></li>
                            <li><a class="dropdown-item" href="#">Eggnog</a></li>
                            <li><a class="dropdown-item" href="#">Amaretto</a></li>
                            <!-- Add the same list of 50 flavors here -->
                            <!-- ... -->
                        </ul>
                    </li>
                   
                </ul>
                <form class="d-flex" role="search">
                    <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                    <button class="btn btn-outline-success" type="submit">Search</button>
                </form>
                <ul class="navbar-nav ml-auto mb-2 mb-lg-0">
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            ABOUT (DEV)
                        </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">history</a></li>
                            <li><a class="dropdown-item" href="#">support</a></li>
                            <li><a class="dropdown-item" href="#">contact</a></li>

                            <!-- Add the same list of 50 flavors here -->
                            <!-- ... -->
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            Stores
                        </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">Tirupati</a></li>
                            <li><a class="dropdown-item" href="#">Visakhapatnam</a></li>
                            <li><a class="dropdown-item" href="#">Vijayawada</a></li>
                            <li><a class="dropdown-item" href="#">Kurnool</a></li>
                            <li><a class="dropdown-item" href="#">Guntur</a></li>
                            <li><a class="dropdown-item" href="#">Rajahmundry</a></li>
                            <li><a class="dropdown-item" href="#">Kakinada</a></li>
                            <li><a class="dropdown-item" href="#">Nellore</a></li>
                            <li><a class="dropdown-item" href="#">Anantapur</a></li>
                            <li><a class="dropdown-item" href="#">Chittoor</a></li>
                            <li><a class="dropdown-item" href="#">Ongole</a></li>
                            <li><a class="dropdown-item" href="#">Eluru</a></li>
                            <!-- Places from Telangana -->
                            <li><a class="dropdown-item" href="#">Hyderabad</a></li>
                            <li><a class="dropdown-item" href="#">Warangal</a></li>
                            <li><a class="dropdown-item" href="#">Nizamabad</a></li>
                            <li><a class="dropdown-item" href="#">Karimnagar</a></li>
                            <li><a class="dropdown-item" href="#">Khammam</a></li>
                            <li><a class="dropdown-item" href="#">Ramagundam</a></li>
                            <li><a class="dropdown-item" href="#">Mahabubnagar</a></li>
                            <li><a class="dropdown-item" href="#">Nalgonda</a></li>
                            <li><a class="dropdown-item" href="#">Adilabad</a></li>
                            <li><a class="dropdown-item" href="#">Suryapet</a></li>
                            <!-- Places from Chennai -->
                            <li><a class="dropdown-item" href="#">Chennai</a></li>
                            <li><a class="dropdown-item" href="#">Coimbatore</a></li>
                            <li><a class="dropdown-item" href="#">Madurai</a></li>
                            <li><a class="dropdown-item" href="#">Tiruchirappalli</a></li>
                            <li><a class="dropdown-item" href="#">Salem</a></li>
                            <li><a class="dropdown-item" href="#">Tirunelveli</a></li>
                            <li><a class="dropdown-item" href="#">Thanjavur</a></li>
                            <li><a class="dropdown-item" href="#">Vellore</a></li>
                            <li><a class="dropdown-item" href="#">Erode</a></li>
                            <li><a class="dropdown-item" href="#">Tiruppur</a></li>
                            <!-- Add the same list of 50 flavors here -->
                            <!-- ... -->
                        </ul>
                   
                </ul>
                
            </div>
        </div>
    </nav><br><br>
   <div><h2><b>Grab your flavour & <br><center>enjoy before it melts</center></b></h2>
   </div>
   
   <div class="container mt-5 text-center">
    <a href="#" class="order-now-btn">
        
        <span class="btn-icon">
            <!-- You can use an icon library like FontAwesome or an emoji -->
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" class="bi bi-cart" viewBox="0 0 16 16">
                <path d="M0 1a1 1 0 0 1 1-1h2a1 1 0 0 1 .98.8L4.89 3H14a1 1 0 0 1 .92 1.38l-3 7A1 1 0 0 1 11 12H4a1 1 0 0 1-.92-.62L.68 1.92A1 1 0 0 1 0 1zM4.1 4l.4 1H12.8l2.2-4H5.09L4.1 4zM3 12a2 2 0 1 1-4 0 2 2 0 0 1 4 0zm10 0a2 2 0 1 1-4 0 2 2 0 0 1 4 0z"/>
            </svg>
        </span>
        Order Now
    </a>
</div>
<div class="container">
    <div class="contact-us-container">
        <a href="https://www.facebook.com/example" class="contact-link" target="_blank"><i class="fab fa-facebook-square"></i> Facebook</a>
        <a href="mailto:contact@example.com" class="contact-link"><i class="fas fa-envelope"></i> Email</a>
        <a href="tel:+1234567890" class="contact-link"><i class="fas fa-phone-alt"></i> Contact</a>
    </div>

    
    


    
   
</body>
</html>

