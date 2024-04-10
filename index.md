---
layout: none
---

<html>
<head>
    <link href="src/output.css" rel="stylesheet">
</head>
<body class="bg-cover bg-[url('/assets/images/home.jpg')] flex justify-center items-center h-screen">
    <div class="flex flex-col items-center w-full px-4">
        <h1 class="text-4xl font-bold text-center text-white mb-2">Barcelona Popup Coffee</h1>
        <h2 class="text-2xl text-center text-gray-300 mb-8">The best coffee in town</h2>
        <div class="w-96 h-64 bg-white flex justify-center items-center shadow-lg rounded-lg">
            {% include form.html %}
        </div>
    </div>
</body>
</html>