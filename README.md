<!DOCTYPE html><html lang="en"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aesthetic Workspaces</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }body {
        font-family: 'Inter', sans-serif;
        background-color: #f4f4f4;
        color: #333;
        line-height: 1.6;
    }

    header {
        background: url('https://images.unsplash.com/photo-1607082352316-258a2bfc0ef4') no-repeat center center/cover;
        height: 90vh;
        color: white;
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;
        padding: 0 2rem;
    }

    header h1 {
        font-size: 3rem;
        background-color: rgba(0, 0, 0, 0.6);
        padding: 1rem 2rem;
        border-radius: 10px;
    }

    section {
        padding: 4rem 2rem;
        max-width: 1000px;
        margin: auto;
    }

    .grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 2rem;
    }

    .card {
        background: white;
        padding: 1.5rem;
        border-radius: 10px;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        transition: transform 0.2s ease;
    }

    .card:hover {
        transform: translateY(-5px);
    }

    .card img {
        width: 100%;
        border-radius: 8px;
    }

    .tips li {
        margin-bottom: 1rem;
    }

    footer {
        background: #222;
        color: white;
        text-align: center;
        padding: 2rem;
    }

    .cta {
        text-align: center;
        margin-top: 3rem;
    }

    .cta a {
        background-color: #222;
        color: white;
        padding: 0.75rem 1.5rem;
        text-decoration: none;
        border-radius: 5px;
        font-weight: bold;
        transition: background 0.3s ease;
    }

    .cta a:hover {
        background-color: #555;
    }
</style>

</head><body>
    <header>
        <h1>Find Your Vibe, Build Your Space</h1>
    </header><section>
    <h2 style="margin-bottom: 1rem;">Workspace Types</h2>
    <div class="grid">
        <div class="card">
            <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c" alt="Student Setup">
            <h3>Student Setup</h3>
            <p>Simple, clean, and distraction-free. Perfect for study marathons.</p>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1616627455402-f2f7343b609c" alt="Coder Setup">
            <h3>Coding Setup</h3>
            <p>Dual monitors, ergonomic chair, mechanical keyboard. Code like a beast.</p>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1585421514286-efb74c2b76e5" alt="Gamer Setup">
            <h3>Gaming Setup</h3>
            <p>RGB lights, ultra-wide screen, and vibes. Let the grind begin.</p>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1584467735871-d208859b622e" alt="Art Desk">
            <h3>Art Desk</h3>
            <p>Cozy and inspiring. A perfect zone for creativity and calm.</p>
        </div>
    </div>
</section>

<section>
    <h2 style="margin-bottom: 1rem;">Quick Tips</h2>
    <ul class="tips">
        <li>Use warm lighting and desk lamps</li>
        <li>Add plants for a chill vibe</li>
        <li>Keep cables hidden for that clean look</li>
        <li>Wall art and minimal decoration = instant mood boost</li>
    </ul>

    <div class="cta">
        <p>Want the ultimate checklist?</p>
        <a href="#">Download Now</a>
    </div>
</section>

<footer>
    <p>Created with love for the aesthetic freaks</p>
</footer>

</body></html>
