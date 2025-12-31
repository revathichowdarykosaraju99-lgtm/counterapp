
<body>
    <h1>CounterApp</h1>
    <p>Count: <span id="count">0</span></p>

    <button onclick="increment()">+</button>
    <button onclick="decrement()">-</button>
    <button onclick="resetCount()">Reset</button>

    <script>
        let count = 0;

        function increment() {
            count++;
            document.getElementById("count").innerText = count;
        }

        function decrement() {
            count--;
            document.getElementById("count").innerText = count;
        }

        function resetCount() {
            count = 0;
            document.getElementById("count").innerText = count;
        }
    </script>








































