<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grid and Flexbox Layout Example</title>
    <style>
        /* Grid Layout */
        .grid-container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            background-color: #f0f0f0;
            padding: 20px;
        }

        .grid-item {
            background-color: #3498db;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        /* Flexbox Layout */
        .flex-container {
            display: flex;
            justify-content: space-between;
            background-color: #333;
            padding: 20px;
            color: #fff;
        }

        .flex-item {
            flex: 1;
            background-color: #e74c3c;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>
    <!-- Grid Layout Section -->
    <section class="grid-container">
        <div class="grid-item">Item 1</div>
        <div class="grid-item">Item 2</div>
        <div class="grid-item">Item 3</div>
    </section>

    <!-- Flexbox Layout Section -->
    <section class="flex-container">
        <div class="flex-item">Flex Item 1</div>
        <div class="flex-item">Flex Item 2</div>
        <div class="flex-item">Flex Item 3</div>
    </section>
</body>
</html>
