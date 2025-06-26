<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Greenn - Collateral-Based Lending</title>
    <!-- Tailwind CSS CDN for modern, responsive styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6; /* Light gray background */
            color: #333;
        }
        /* Custom green theme colors */
        .bg-greenn-primary {
            background-color: #2e7d32; /* Dark green */
        }
        .text-greenn-primary {
            color: #2e7d32; /* Dark green */
        }
        .border-greenn-primary {
            border-color: #2e7d32; /* Dark green */
        }
        .hover\:bg-greenn-darker:hover {
            background-color: #1b5e20; /* Even darker green for hover */
        }
        .btn-primary {
            @apply bg-greenn-primary text-white px-6 py-3 rounded-full hover:bg-greenn-darker transition duration-300 ease-in-out shadow-lg;
        }
        /* Custom styling for rounded cards/boxes */
        .card {
            @apply bg-white p-8 rounded-lg shadow-md hover:shadow-lg transition duration-300 ease-in-out;
        }
        /* Hidden success messages by default */
        .success-message {
            @apply mt-4 p-3 rounded-md bg-green-100 text-green-700 hidden;
        }
    </style>
</head>
<body class="antialiased">

    <!-- Header Section -->
    <header class="bg-greenn-primary text-white py-4 shadow-lg">
        <div class="container mx-auto px-4 flex justify-between items-center">
            <h1 class="text-3xl font-bold">Greenn</h1>
            <nav>
                <ul class="flex space-x-6">
                    <li><a href="#home" class="hover:text-green-200 transition duration-200">Home</a></li>
                    <li><a href="#loan-application" class="hover:text-green-200 transition duration-200">Apply for Loan</a></li>
                    <li><a href="#contact" class="hover:text-green-200 transition duration-200">Contact Us</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section / Homepage Intro -->
    <section id="home" class="bg-gradient-to-r from-green-600 to-greenn-primary text-white py-20 px-4 text-center">
        <div class="container mx-auto">
            <h2 class="text-5xl font-extrabold mb-6 leading-tight">Greenn: Your Partner in Collateral-Based Lending</h2>
            <p class="text-xl mb-8 max-w-3xl mx-auto">
                Greenn provides accessible and secure collateral-based financial solutions to individuals and small businesses in Zambia, fostering economic stability and growth.
            </p>
            <a href="#loan-application" class="btn-primary">Apply for a Loan Today!</a>
        </div>
    </section>

    <!-- Mission, Vision, and Values Section -->
    <section class="py-16 px-4 bg-white">
        <div class="container mx-auto text-center">
            <h3 class="text-4xl font-bold text-greenn-primary mb-12">Our Foundation</h3>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Mission Card -->
                <div class="card">
                    <h4 class="text-2xl font-semibold mb-4 text-greenn-primary">Our Mission</h4>
                    <p class="text-gray-700">To deliver accessible and secure collateral-based financial solutions, rooted in integrity and economic empowerment for Zambian communities.</p>
                </div>
                <!-- Vision Card -->
                <div class="card">
                    <h4 class="text-2xl font-semibold mb-4 text-greenn-primary">Our Vision</h4>
                    <p class="text-gray-700">To become Zambia’s most reliable and inclusive grassroots financing enterprise.</p>
                </div>
                <!-- Values Card -->
                <div class="card">
                    <h4 class="text-2xl font-semibold mb-4 text-greenn-primary">Core Values</h4>
                    <ul class="list-disc list-inside text-gray-700 space-y-2">
                        <li>Integrity</li>
                        <li>Efficiency</li>
                        <li>Innovation</li>
                        <li>Trust</li>
                        <li>Community-Centered</li>
                    </ul>
                </div>
            </div>
            <div class="mt-12">
                <h4 class="text-3xl font-bold mb-4 text-greenn-primary">Meet Our Founder</h4>
                <!-- Founder Image -->
                <div class="flex justify-center mb-6">
                    <img src="WhatsApp Image 2025-06-06 at 10.11.18 AM.jpeg-97baf1bf-5761-486b-85bd-938eff2bb9b9" alt="Patrick Kondowe, Founder of Greenn" class="rounded-full w-48 h-48 object-cover shadow-lg border-4 border-greenn-primary">
                </div>
                <p class="text-lg text-gray-700 max-w-2xl mx-auto">
                    Greenn was founded by <strong class="text-greenn-primary">Patrick Kondowe</strong>, who holds a B.A. in Economics with Demography from the University of Zambia. Patrick's vision drives Greenn's commitment to inclusive growth.
                </p>
            </div>
        </div>
    </section>

    <!-- Collateral-Based Lending Section (Simplified from previous Business Units) -->
    <section class="py-16 px-4 bg-gray-100">
        <div class="container mx-auto text-center">
            <h3 class="text-4xl font-bold text-greenn-primary mb-12">Our Loan Services</h3>
            <div class="max-w-3xl mx-auto">
                <div class="card border-t-4 border-greenn-primary">
                    <div class="text-5xl mb-4 text-greenn-primary">💰</div>
                    <h4 class="text-2xl font-semibold mb-4">Collateral-Based Lending</h4>
                    <p class="text-gray-700 mb-4">
                        At Greenn, we understand the need for quick and reliable access to capital. Our collateral-based lending services provide secure financial solutions, allowing you to leverage your valuable assets to get the funds you need. We offer a straightforward and transparent process designed for your convenience.
                    </p>
                    <p class="text-gray-700">
                        Whether you're looking to invest in your business, cover unexpected expenses, or seize new opportunities, Greenn is here to help.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Loan Application Form Section -->
    <section id="loan-application" class="py-16 px-4 bg-white">
        <div class="container mx-auto max-w-xl">
            <h3 class="text-4xl font-bold text-greenn-primary mb-8 text-center">Loan Application Form</h3>
            <div class="card">
                <form id="loanApplicationForm" class="space-y-6">
                    <div>
                        <label for="fullName" class="block text-gray-700 text-sm font-bold mb-2">Full Name:</label>
                        <input type="text" id="fullName" name="fullName" required class="shadow appearance-none border rounded-lg w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-greenn-primary">
                    </div>
                    <div>
                        <label for="email" class="block text-gray-700 text-sm font-bold mb-2">Email:</label>
                        <input type="email" id="email" name="email" required class="shadow appearance-none border rounded-lg w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-greenn-primary">
                    </div>
                    <div>
                        <label for="phone" class="block text-gray-700 text-sm font-bold mb-2">Phone Number:</label>
                        <input type="tel" id="phone" name="phone" pattern="[0-9]{10,}" title="Please enter a valid phone number (e.g., 0977123456)" required class="shadow appearance-none border rounded-lg w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-greenn-primary">
                    </div>
                    <div>
                        <label for="loanAmount" class="block text-gray-700 text-sm font-bold mb-2">Loan Amount (ZMW):</label>
                        <input type="number" id="loanAmount" name="loanAmount" min="100" required class="shadow appearance-none border rounded-lg w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-greenn-primary">
                    </div>
                    <div>
                        <label for="loanReason" class="block text-gray-700 text-sm font-bold mb-2">Reason for Loan:</label>
                        <textarea id="loanReason" name="loanReason" rows="4" required class="shadow appearance-none border rounded-lg w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-greenn-primary"></textarea>
                    </div>
                    <div class="flex items-center justify-center">
                        <button type="submit" class="btn-primary">Submit Loan Application</button>
                    </div>
                    <div id="loanSuccessMessage" class="success-message">
                        Your loan application has been submitted successfully! We will contact you shortly.
                    </div>
                </form>
            </div>
        </div>
    </section>

    <!-- Callback/Contact Request Form Section -->
    <section id="contact" class="py-16 px-4 bg-gray-100">
        <div class="container mx-auto max-w-xl">
            <h3 class="text-4xl font-bold text-greenn-primary mb-8 text-center">Contact Us / Request a Callback</h3>
            <div class="card">
                <form id="contactForm" class="space-y-6">
                    <div>
                        <label for="contactName" class="block text-gray-700 text-sm font-bold mb-2">Your Name:</label>
                        <input type="text" id="contactName" name="contactName" required class="shadow appearance-none border rounded-lg w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-greenn-primary">
                    </div>
                    <div>
                        <label for="contactPhone" class="block text-gray-700 text-sm font-bold mb-2">Phone Number:</label>
                        <input type="tel" id="contactPhone" name="contactPhone" pattern="[0-9]{10,}" title="Please enter a valid phone number (e.g., 0977123456)" required class="shadow appearance-none border rounded-lg w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-greenn-primary">
                    </div>
                    <div>
                        <label for="contactEmail" class="block text-gray-700 text-sm font-bold mb-2">Email (Optional):</label>
                        <input type="email" id="contactEmail" name="contactEmail" class="shadow appearance-none border rounded-lg w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-greenn-primary">
                    </div>
                    <div class="flex items-center justify-center">
                        <button type="submit" class="btn-primary">Request Callback</button>
                    </div>
                    <div id="contactSuccessMessage" class="success-message">
                        Your contact request has been received! We will get back to you soon.
                    </div>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer class="bg-greenn-primary text-white py-8 px-4 mt-12">
        <div class="container mx-auto text-center md:flex md:justify-between md:items-center">
            <div class="mb-4 md:mb-0">
                <h4 class="text-xl font-semibold mb-2">Greenn</h4>
                <p>&copy; 2025 Greenn. All rights reserved.</p>
            </div>
            <div>
                <h4 class="text-xl font-semibold mb-2">Contact Details</h4>
                <p>Email: info@greenn.zm</p>
                <p>Phone: +260 977 123456</p>
                <p>Location: Lusaka, Zambia (near UNZA)</p>
            </div>
        </div>
    </footer>

    <script>
        // JavaScript for form validation and submission messages

        // Get references to the forms and success messages
        const loanApplicationForm = document.getElementById('loanApplicationForm');
        const loanSuccessMessage = document.getElementById('loanSuccessMessage');
        const contactForm = document.getElementById('contactForm');
        const contactSuccessMessage = document.getElementById('contactSuccessMessage');

        /**
         * Generic function to handle form submission.
         * Hides the form and displays a success message.
         * @param {Event} event - The form submission event.
         * @param {HTMLElement} formElement - The form HTML element.
         * @param {HTMLElement} successMessageElement - The success message HTML element.
         */
        function handleFormSubmission(event, formElement, successMessageElement) {
            event.preventDefault(); // Prevent default form submission

            // Basic client-side validation
            if (!formElement.checkValidity()) {
                // If the form is not valid, the browser will show its default validation messages
                formElement.reportValidity();
                return;
            }

            // Hide the form
            formElement.style.display = 'none';

            // Show the success message
            successMessageElement.style.display = 'block';

            // Optional: You might want to reset the form after a short delay
            // setTimeout(() => {
            //     formElement.reset();
            //     formElement.style.display = 'block';
            //     successMessageElement.style.display = 'none';
            // }, 5000); // Resets after 5 seconds
        }

        // Add event listener for loan application form submission
        loanApplicationForm.addEventListener('submit', (event) => {
            handleFormSubmission(event, loanApplicationForm, loanSuccessMessage);
        });

        // Add event listener for contact form submission
        contactForm.addEventListener('submit', (event) => {
            handleFormSubmission(event, contactForm, contactSuccessMessage);
        });

        // Smooth scrolling for navigation links
        document.querySelectorAll('nav a').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();

                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
