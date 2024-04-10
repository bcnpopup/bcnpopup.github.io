---
layout: none
---

<html>
<head>
    <link href="src/output.css" rel="stylesheet">
</head>
<body class="bg-cover bg-[url('/assets/images/home.jpg')] flex justify-center items-center min-h-screen">
    <div class="flex flex-col items-center w-full px-4">
        <h1 class="text-4xl font-bold text-center text-white mb-2">Barcelona Popup Coffee</h1>
        <h2 class="text-2xl text-center text-gray-300 mb-8">The best coffee in town</h2>
        <form action="https://formspree.io/f/mqkrgdqq" method="POST" class="w-full max-w-2xl flex flex-col justify-center items-center bg-gray-100 p-4 sm:p-8 rounded-lg">
            <div class="mb-4 w-full">
                <input type="email" name="email" id="email" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-amber-400 focus:ring-amber-400" placeholder="you@example.com">
            </div>
            <div class="mb-6 w-full">
                <textarea name="message" id="message" rows="4" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-amber-400 focus:ring-amber-400" placeholder="Enter your message..."></textarea>
            </div>
            <button type="submit" class="w-full flex justify-center py-2 px-4 border border-transparent rounded-md shadow-sm text-sm font-medium text-white bg-amber-600 hover:bg-amber-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-amber-500">
                Send
            </button>
        </form>
    </div>
</body>
</html>