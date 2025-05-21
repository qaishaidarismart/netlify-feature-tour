<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <title>
   Social Media Hub
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
 <body class="bg-gray-50 min-h-screen flex flex-col">
  <header class="bg-white shadow-md">
   <div class="container mx-auto px-4 py-4 flex items-center justify-between">
    <h1 class="text-2xl font-semibold text-gray-800">
     My Social Media Hub
    </h1>
    <nav class="space-x-4 text-gray-600">
     <a class="hover:text-blue-600 transition" href="#social-links">
      Social Links
     </a>
     <a class="hover:text-blue-600 transition" href="#messages">
      Messages
     </a>
     <a class="hover:text-blue-600 transition" href="#contact-form">
      Send Message
     </a>
    </nav>
   </div>
  </header>
  <main class="flex-grow container mx-auto px-4 py-8">
   <!-- Social Media Links Section -->
   <section class="mb-12" id="social-links">
    <h2 class="text-3xl font-bold text-gray-800 mb-6 text-center">
     Connect with Me
    </h2>
    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-8 max-w-4xl mx-auto">
     <a aria-label="Facebook Profile" class="flex flex-col items-center space-y-2 hover:text-blue-600 transition" href="https://www.facebook.com/yourprofile" rel="noopener noreferrer" target="_blank">
      <img alt="Facebook logo in blue and white" class="w-20 h-20 object-contain" height="80" src="https://storage.googleapis.com/a1aa/image/627ace6d-bfec-4f18-6a08-680b0c02451d.jpg" width="80"/>
      <span class="text-lg font-medium">
       Facebook
      </span>
     </a>
     <a aria-label="Twitter Profile" class="flex flex-col items-center space-y-2 hover:text-sky-500 transition" href="https://twitter.com/yourprofile" rel="noopener noreferrer" target="_blank">
      <img alt="Twitter logo in light blue and white" class="w-20 h-20 object-contain" height="80" src="https://storage.googleapis.com/a1aa/image/97eaf815-733c-4d9f-e681-5f9f8ffc0111.jpg" width="80"/>
      <span class="text-lg font-medium">
       Twitter
      </span>
     </a>
     <a aria-label="Instagram Profile" class="flex flex-col items-center space-y-2 hover:text-pink-600 transition" href="https://www.instagram.com/yourprofile" rel="noopener noreferrer" target="_blank">
      <img alt="Instagram logo with gradient pink, orange, and purple" class="w-20 h-20 object-contain" height="80" src="https://storage.googleapis.com/a1aa/image/cde82e0c-ff20-4cba-70b3-02110976639b.jpg" width="80"/>
      <span class="text-lg font-medium">
       Instagram
      </span>
     </a>
     <a aria-label="LinkedIn Profile" class="flex flex-col items-center space-y-2 hover:text-blue-700 transition" href="https://www.linkedin.com/in/yourprofile" rel="noopener noreferrer" target="_blank">
      <img alt="LinkedIn logo in blue and white" class="w-20 h-20 object-contain" height="80" src="https://storage.googleapis.com/a1aa/image/adb05e27-5b38-4a20-c472-594ba9d38afd.jpg" width="80"/>
      <span class="text-lg font-medium">
       LinkedIn
      </span>
     </a>
     <a aria-label="Telegram Profile" class="flex flex-col items-center space-y-2 hover:text-blue-400 transition" href="https://t.me/yourprofile" rel="noopener noreferrer" target="_blank">
      <img alt="Telegram logo in light blue and white paper plane" class="w-20 h-20 object-contain" height="80" src="https://storage.googleapis.com/a1aa/image/1c30e5f7-aae9-42a1-e73d-7b2c44780f5a.jpg" width="80"/>
      <span class="text-lg font-medium">
       Telegram
      </span>
     </a>
    </div>
   </section>
   <!-- Messages Section -->
   <section class="mb-12 max-w-4xl mx-auto" id="messages">
    <h2 class="text-3xl font-bold text-gray-800 mb-6 text-center">
     Received Messages
    </h2>
    <div aria-live="polite" aria-relevant="additions" class="bg-white rounded-lg shadow-md p-6 max-h-96 overflow-y-auto border border-gray-200" id="messages-container">
     <p class="text-gray-500 text-center">
      No messages yet. Your messages will appear here.
     </p>
    </div>
   </section>
   <!-- Send Message Form -->
   <section class="max-w-4xl mx-auto bg-white rounded-lg shadow-md p-8" id="contact-form">
    <h2 class="text-3xl font-bold text-gray-800 mb-6 text-center">
     Send Me a Message
    </h2>
    <form aria-label="Send message form" class="space-y-6" id="messageForm">
     <div>
      <label class="block text-gray-700 font-semibold mb-2" for="name">
       Name
      </label>
      <input class="w-full border border-gray-300 rounded-md px-4 py-2 focus:outline-none focus:ring-2 focus:ring-blue-500" id="name" name="name" placeholder="Your full name" required="" type="text"/>
     </div>
     <div>
      <label class="block text-gray-700 font-semibold mb-2" for="email">
       Email
      </label>
      <input class="w-full border border-gray-300 rounded-md px-4 py-2 focus:outline-none focus:ring-2 focus:ring-blue-500" id="email" name="email" placeholder="your.email@example.com" required="" type="email"/>
     </div>
     <div>
      <label class="block text-gray-700 font-semibold mb-2" for="platform">
       Preferred Platform
      </label>
      <select class="w-full border border-gray-300 rounded-md px-4 py-2 focus:outline-none focus:ring-2 focus:ring-blue-500" id="platform" name="platform" required="">
       <option disabled="" selected="" value="">
        Select a platform
       </option>
       <option value="Facebook">
        Facebook
       </option>
       <option value="Twitter">
        Twitter
       </option>
       <option value="Instagram">
        Instagram
       </option>
       <option value="LinkedIn">
        LinkedIn
       </option>
       <option value="Telegram">
        Telegram
       </option>
      </select>
     </div>
     <div>
      <label class="block text-gray-700 font-semibold mb-2" for="message">
       Message
      </label>
      <textarea class="w-full border border-gray-300 rounded-md px-4 py-2 focus:outline-none focus:ring-2 focus:ring-blue-500" id="message" name="message" placeholder="Write your message here..." required="" rows="4"></textarea>
     </div>
     <button class="w-full bg-blue-600 text-white font-semibold py-3 rounded-md hover:bg-blue-700 transition" type="submit">
      Send Message
     </button>
    </form>
    <p class="mt-4 text-center text-green-600 font-semibold hidden" id="formStatus">
    </p>
   </section>
  </main>
  <footer class="bg-white border-t border-gray-200 py-6 mt-12">
   <div class="container mx-auto px-4 text-center text-gray-600">
    © 2024 My Social Media Hub. All rights reserved.
   </div>
  </footer>
  <script>
   // Messages array to store messages in-memory
    const messages = [];

    const form = document.getElementById('messageForm');
    const messagesContainer = document.getElementById('messages-container');
    const formStatus = document.getElementById('formStatus');

    function renderMessages() {
      if (messages.length === 0) {
        messagesContainer.innerHTML =
          '<p class="text-gray-500 text-center">No messages yet. Your messages will appear here.</p>';
        return;
      }

      messagesContainer.innerHTML = messages
        .map(
          (msg) => `
        <div class="border-b border-gray-200 py-4 last:border-b-0">
          <div class="flex items-center justify-between mb-1">
            <h3 class="font-semibold text-gray-800">${escapeHtml(msg.name)}</h3>
            <span class="text-sm text-gray-500">${new Date(msg.date).toLocaleString()}</span>
          </div>
          <p class="text-gray-600 mb-1"><strong>Email:</strong> <a href="mailto:${escapeHtml(
            msg.email
          )}" class="text-blue-600 hover:underline">${escapeHtml(msg.email)}</a></p>
          <p class="text-gray-600 mb-1"><strong>Platform:</strong> ${escapeHtml(msg.platform)}</p>
          <p class="text-gray-700 whitespace-pre-line">${escapeHtml(msg.message)}</p>
        </div>
      `
        )
        .join('');
    }

    // Escape HTML to prevent XSS
    function escapeHtml(text) {
      return text
        .replace(/&/g, '&amp;')
        .replace(/</g, '&lt;')
        .replace(/>/g, '&gt;')
        .replace(/"/g, '&quot;')
        .replace(/'/g, '&#039;');
    }

    form.addEventListener('submit', (e) => {
      e.preventDefault();

      const name = form.name.value.trim();
      const email = form.email.value.trim();
      const platform = form.platform.value;
      const message = form.message.value.trim();

      if (!name || !email || !platform || !message) {
        formStatus.textContent = 'Please fill in all fields.';
        formStatus.classList.remove('hidden', 'text-green-600');
        formStatus.classList.add('text-red-600');
        return;
      }

      // Add message to messages array
      messages.unshift({
        name,
        email,
        platform,
        message,
        date: new Date().toISOString(),
      });

      // Reset form
      form.reset();

      // Show success message
      formStatus.textContent = 'Message sent successfully!';
      formStatus.classList.remove('hidden', 'text-red-600');
      formStatus.classList.add('text-green-600');

      // Re-render messages
      renderMessages();

      // Hide success message after 4 seconds
      setTimeout(() => {
        formStatus.classList.add('hidden');
      }, 4000);
    });

    // Initial render
    renderMessages();
  </script>
 </body>
</html>
