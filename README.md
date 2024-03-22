
<body>
    <header id="home">
      <nav class="navbar">
        <h1>Eventic</h1>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#events">Events</a></li>
            <li><a href="#add-event">New Event</a></li>
        </ul>
      </nav>
      <div class="welcome-event"></div>
    </header>
    <main>
        <section id="events">
            <h1 class="section-title">Events</h1>
            <div class="events-container"></div>
        </section>
        <section id="add-event">
            <h1 class="section-title">New Event</h1>
            <form class="form">
                <input type="text" id="name" placeholder="Name">
                <input type="number" id="attendee" placeholder="Attendees">
                <textarea id="description" cols="30" rows="10" placeholder="Description..."></textarea>
                <select id="status">
                    <option value="0">Free</option>
                    <option value="1">Paid</option>
                </select>
                <button class="btn btn-primary">Save</button>
            </form>
        </section>
    </main>
    <script src="https://www.gstatic.com/firebasejs/7.9.1/firebase-app.js"></script>
<script src="https://www.gstatic.com/firebasejs/7.9.1/firebase-firestore.js"></script>

<script>
 


</body>
</html>
