<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <title>
   Responsive Tailwind Website
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&amp;display=swap" rel="stylesheet"/>
  <style>
   body {
      font-family: 'Inter', sans-serif;
    }
  </style>
 </head>
 <body class="bg-gray-50 text-gray-800">
  <!-- Header / Navbar -->
  <header class="bg-white shadow-md sticky top-0 z-50">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex justify-between items-center h-16">
     <a class="flex items-center space-x-2" href="#">
      <img alt="Company logo with stylized letter C in blue and white" class="h-10 w-10" height="40" src="https://storage.googleapis.com/a1aa/image/bcc498c9-cea3-4b7c-79ab-66420710bfea.jpg" width="40"/>
      <span class="text-2xl font-semibold text-blue-600">
       Company
      </span>
     </a>
     <nav class="hidden md:flex space-x-8 text-gray-700 font-medium">
      <a class="hover:text-blue-600 transition" href="#">
       Home
      </a>
      <a class="hover:text-blue-600 transition" href="#">
       About
      </a>
      <a class="hover:text-blue-600 transition" href="#">
       Services
      </a>
      <a class="hover:text-blue-600 transition" href="#">
       Blog
      </a>
      <a class="hover:text-blue-600 transition" href="#">
       Contact
      </a>
     </nav>
     <div class="md:hidden">
      <button aria-label="Toggle menu" class="text-gray-700 focus:outline-none focus:ring-2 focus:ring-blue-600" id="mobile-menu-button">
       <i class="fas fa-bars fa-lg">
       </i>
      </button>
     </div>
    </div>
   </div>
   <nav class="md:hidden hidden bg-white border-t border-gray-200" id="mobile-menu">
    <a class="block px-4 py-3 text-gray-700 hover:bg-blue-50 hover:text-blue-600 transition" href="#">
     Home
    </a>
    <a class="block px-4 py-3 text-gray-700 hover:bg-blue-50 hover:text-blue-600 transition" href="#">
     About
    </a>
    <a class="block px-4 py-3 text-gray-700 hover:bg-blue-50 hover:text-blue-600 transition" href="#">
     Services
    </a>
    <a class="block px-4 py-3 text-gray-700 hover:bg-blue-50 hover:text-blue-600 transition" href="#">
     Blog
    </a>
    <a class="block px-4 py-3 text-gray-700 hover:bg-blue-50 hover:text-blue-600 transition" href="#">
     Contact
    </a>
   </nav>
  </header>
  <!-- Hero Section -->
  <section class="bg-white">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16 flex flex-col-reverse md:flex-row items-center md:items-start gap-12">
    <div class="md:w-1/2 text-center md:text-left">
     <h1 class="text-4xl sm:text-5xl font-extrabold text-gray-900 leading-tight">
      Empower Your Business with Our Solutions
     </h1>
     <p class="mt-6 text-lg text-gray-600">
      We provide innovative and tailored services to help your business grow and succeed in the digital age.
     </p>
     <div class="mt-8 flex justify-center md:justify-start space-x-4">
      <a class="inline-block px-6 py-3 bg-blue-600 text-white font-semibold rounded-md shadow hover:bg-blue-700 transition" href="#">
       Get Started
      </a>
      <a class="inline-block px-6 py-3 border border-blue-600 text-blue-600 font-semibold rounded-md hover:bg-blue-50 transition" href="#">
       Learn More
      </a>
     </div>
    </div>
    <div class="md:w-1/2">
     <img alt="A diverse business team collaborating in a modern office with laptops and charts on the table" class="w-full rounded-lg shadow-lg" height="400" src="https://storage.googleapis.com/a1aa/image/9b09ab7d-ec0e-4580-b24a-031a1b18c171.jpg" width="600"/>
    </div>
   </div>
  </section>
  <!-- Services Section -->
  <section class="bg-gray-100 py-16">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <h2 class="text-3xl font-extrabold text-gray-900 text-center">
     Our Services
    </h2>
    <p class="mt-4 max-w-2xl mx-auto text-center text-gray-600 text-lg">
     Explore the wide range of services we offer to help your business thrive.
    </p>
    <div class="mt-12 grid gap-8 sm:grid-cols-2 lg:grid-cols-4">
     <div class="bg-white rounded-lg shadow p-6 flex flex-col items-center text-center">
      <img alt="Icon representing business consulting with a person giving advice" class="mb-4" height="80" src="https://storage.googleapis.com/a1aa/image/d71b7a89-b663-4cb9-4ec6-d2d9100919ac.jpg" width="80"/>
      <h3 class="text-xl font-semibold text-gray-900">
       Business Consulting
      </h3>
      <p class="mt-2 text-gray-600">
       Expert advice to optimize your business strategy and operations.
      </p>
     </div>
     <div class="bg-white rounded-lg shadow p-6 flex flex-col items-center text-center">
      <img alt="Icon representing digital marketing with a megaphone and social media symbols" class="mb-4" height="80" src="https://storage.googleapis.com/a1aa/image/4a13491b-b627-4918-4660-dfaacb04735a.jpg" width="80"/>
      <h3 class="text-xl font-semibold text-gray-900">
       Digital Marketing
      </h3>
      <p class="mt-2 text-gray-600">
       Boost your online presence and reach your target audience effectively.
      </p>
     </div>
     <div class="bg-white rounded-lg shadow p-6 flex flex-col items-center text-center">
      <img alt="Icon representing software development with code brackets and gears" class="mb-4" height="80" src="https://storage.googleapis.com/a1aa/image/2db10859-ec69-41aa-e028-fdc0767a7da5.jpg" width="80"/>
      <h3 class="text-xl font-semibold text-gray-900">
       Software Development
      </h3>
      <p class="mt-2 text-gray-600">
       Custom software solutions tailored to your business needs.
      </p>
     </div>
     <div class="bg-white rounded-lg shadow p-6 flex flex-col items-center text-center">
      <img alt="Icon representing customer support with headset and chat bubbles" class="mb-4" height="80" src="https://storage.googleapis.com/a1aa/image/24feff88-5d16-45fb-6d6b-fbf4a5cd9549.jpg" width="80"/>
      <h3 class="text-xl font-semibold text-gray-900">
       Customer Support
      </h3>
      <p class="mt-2 text-gray-600">
       Reliable support to keep your business running smoothly.
      </p>
     </div>
    </div>
   </div>
  </section>
  <!-- Latest News Section -->
  <section class="bg-white py-16">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <h2 class="text-3xl font-extrabold text-gray-900 text-center">
     Latest News
    </h2>
    <p class="mt-4 max-w-2xl mx-auto text-center text-gray-600 text-lg">
     Stay updated with the latest trends and insights from our experts.
    </p>
    <div class="mt-12 grid gap-10 sm:grid-cols-2 lg:grid-cols-3">
     <article class="bg-gray-50 rounded-lg shadow overflow-hidden flex flex-col">
      <img alt="Photo of a large tech conference with a speaker on stage and audience in a modern convention center" class="w-full object-cover h-48" height="350" src="https://storage.googleapis.com/a1aa/image/57a96759-bbb1-4eea-ae6d-0f71cc193566.jpg" width="600"/>
      <div class="p-6 flex flex-col flex-grow">
       <h3 class="text-xl font-semibold text-gray-900">
        Tech Conference 2024 Highlights
       </h3>
       <p class="mt-3 text-gray-600 flex-grow">
        Discover the key takeaways and innovations presented at this year’s biggest tech event.
       </p>
       <a class="mt-4 inline-flex items-center text-blue-600 font-semibold hover:underline" href="#">
        Read More
        <i class="fas fa-arrow-right ml-2">
        </i>
       </a>
      </div>
     </article>
     <article class="bg-gray-50 rounded-lg shadow overflow-hidden flex flex-col">
      <img alt="Image of a marketing team brainstorming ideas with charts and laptops in a bright office" class="w-full object-cover h-48" height="350" src="https://storage.googleapis.com/a1aa/image/6959df60-28cf-4dd5-5964-a1a7333ea2b1.jpg" width="600"/>
      <div class="p-6 flex flex-col flex-grow">
       <h3 class="text-xl font-semibold text-gray-900">
        Top Marketing Tips for 2024
       </h3>
       <p class="mt-3 text-gray-600 flex-grow">
        Learn the latest strategies to enhance your digital marketing campaigns this year.
       </p>
       <a class="mt-4 inline-flex items-center text-blue-600 font-semibold hover:underline" href="#">
        Read More
        <i class="fas fa-arrow-right ml-2">
        </i>
       </a>
      </div>
     </article>
     <article class="bg-gray-50 rounded-lg shadow overflow-hidden flex flex-col">
      <img alt="Photo of a customer support representative smiling with headset in a modern call center" class="w-full object-cover h-48" height="350" src="https://storage.googleapis.com/a1aa/image/f673a370-5cb5-42cd-a727-17c47a168c7b.jpg" width="600"/>
      <div class="p-6 flex flex-col flex-grow">
       <h3 class="text-xl font-semibold text-gray-900">
        Customer Support Best Practices
       </h3>
       <p class="mt-3 text-gray-600 flex-grow">
        Enhance your customer satisfaction with these proven support techniques.
       </p>
       <a class="mt-4 inline-flex items-center text-blue-600 font-semibold hover:underline" href="#">
        Read More
        <i class="fas fa-arrow-right ml-2">
        </i>
       </a>
      </div>
     </article>
    </div>
   </div>
  </section>
  <!-- Testimonials Section -->
  <section class="bg-gray-100 py-16">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <h2 class="text-3xl font-extrabold text-gray-900 text-center">
     What Our Clients Say
    </h2>
    <div class="mt-12 grid gap-8 sm:grid-cols-2 lg:grid-cols-3">
     <div class="bg-white rounded-lg shadow p-6 flex flex-col">
      <p class="text-gray-700 italic flex-grow">
       “The team’s expertise and dedication helped us increase our revenue by 40% in just six months.”
      </p>
      <div class="mt-6 flex items-center space-x-4">
       <img alt="Portrait of John Doe, a middle-aged man with short brown hair and glasses smiling" class="w-16 h-16 rounded-full object-cover" height="64" src="https://storage.googleapis.com/a1aa/image/9b19fd16-1660-46db-f540-dc078a72e9a7.jpg" width="64"/>
       <div>
        <p class="font-semibold text-gray-900">
         John Doe
        </p>
        <p class="text-gray-600 text-sm">
         CEO, Acme Corp
        </p>
       </div>
      </div>
     </div>
     <div class="bg-white rounded-lg shadow p-6 flex flex-col">
      <p class="text-gray-700 italic flex-grow">
       “Their marketing strategies transformed our brand’s online presence and engagement.”
      </p>
      <div class="mt-6 flex items-center space-x-4">
       <img alt="Portrait of Alice Smith, a young woman with curly black hair and bright smile" class="w-16 h-16 rounded-full object-cover" height="64" src="https://storage.googleapis.com/a1aa/image/c602bca1-2db7-4c6a-470f-16d4a4fe46cb.jpg" width="64"/>
       <div>
        <p class="font-semibold text-gray-900">
         Alice Smith
        </p>
        <p class="text-gray-600 text-sm">
         Marketing Director, Bright Ideas
        </p>
       </div>
      </div>
     </div>
     <div class="bg-white rounded-lg shadow p-6 flex flex-col">
      <p class="text-gray-700 italic flex-grow">
       “Excellent customer support that is always available and quick to resolve issues.”
      </p>
      <div class="mt-6 flex items-center space-x-4">
       <img alt="Portrait of Michael Williams, a man with short gray hair and friendly expression" class="w-16 h-16 rounded-full object-cover" height="64" src="https://storage.googleapis.com/a1aa/image/5f005d0d-b847-4e66-aeee-a5830d9a925b.jpg" width="64"/>
       <div>
        <p class="font-semibold text-gray-900">
         Michael Williams
        </p>
        <p class="text-gray-600 text-sm">
         Operations Manager, Tech Solutions
        </p>
       </div>
      </div>
     </div>
    </div>
   </div>
  </section>
  <!-- Call to Action Section -->
  <section class="bg-blue-600 py-16">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center text-white">
    <h2 class="text-4xl font-extrabold">
     Ready to take your business to the next level?
    </h2>
    <p class="mt-4 text-lg max-w-2xl mx-auto">
     Contact us today and let’s start building your success story together.
    </p>
    <a class="mt-8 inline-block px-8 py-4 bg-white text-blue-600 font-semibold rounded-md shadow hover:bg-gray-100 transition" href="#">
     Contact Us
    </a>
   </div>
  </section>
  <!-- Footer -->
  <footer class="bg-gray-900 text-gray-300 py-12">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid grid-cols-1 md:grid-cols-4 gap-8">
    <div>
     <h3 class="text-white text-xl font-semibold mb-4">
      Company
     </h3>
     <p class="text-gray-400 max-w-xs">
      We are committed to delivering the best solutions to help your business grow and succeed.
     </p>
     <div class="mt-6 flex space-x-4">
      <a aria-label="Facebook" class="hover:text-white" href="#">
       <i class="fab fa-facebook fa-lg">
       </i>
      </a>
      <a aria-label="Twitter" class="hover:text-white" href="#">
       <i class="fab fa-twitter fa-lg">
       </i>
      </a>
      <a aria-label="LinkedIn" class="hover:text-white" href="#">
       <i class="fab fa-linkedin fa-lg">
       </i>
      </a>
      <a aria-label="Instagram" class="hover:text-white" href="#">
       <i class="fab fa-instagram fa-lg">
       </i>
      </a>
     </div>
    </div>
    <div>
     <h3 class="text-white text-xl font-semibold mb-4">
      Quick Links
     </h3>
     <ul class="space-y-2">
      <li>
       <a class="hover:text-white transition" href="#">
        Home
       </a>
      </li>
      <li>
       <a class="hover:text-white transition" href="#">
        About
       </a>
      </li>
      <li>
       <a class="hover:text-white transition" href="#">
        Services
       </a>
      </li>
      <li>
       <a class="hover:text-white transition" href="#">
        Blog
       </a>
      </li>
      <li>
       <a class="hover:text-white transition" href="#">
        Contact
       </a>
      </li>
     </ul>
    </div>
    <div>
     <h3 class="text-white text-xl font-semibold mb-4">
      Resources
     </h3>
     <ul class="space-y-2">
      <li>
       <a class="hover:text-white transition" href="#">
        Help Center
       </a>
      </li>
      <li>
       <a class="hover:text-white transition" href="#">
        Privacy Policy
       </a>
      </li>
      <li>
       <a class="hover:text-white transition" href="#">
        Terms of Service
       </a>
      </li>
      <li>
       <a class="hover:text-white transition" href="#">
        FAQs
       </a>
      </li>
     </ul>
    </div>
    <div>
     <h3 class="text-white text-xl font-semibold mb-4">
      Contact Us
     </h3>
     <address class="not-italic space-y-2 text-gray-400">
      <p>
       123 Business Rd.
      </p>
      <p>
       Business City, BC 12345
      </p>
      <p>
       Phone: (123) 456-7890
      </p>
      <p>
       Email: contact@company.com
      </p>
     </address>
    </div>
   </div>
   <div class="mt-12 border-t border-gray-800 pt-6 text-center text-gray-500 text-sm">
    © 2024 Company. All rights reserved.
   </div>
  </footer>
  <script>
   const menuButton = document.getElementById('mobile-menu-button');
    const mobileMenu = document.getElementById('mobile-menu');

    menuButton.addEventListener('click', () => {
      mobileMenu.classList.toggle('hidden');
    });
  </script>
 </body>
</html>
