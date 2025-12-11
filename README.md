# CPE-411-CPE22S4---Interactive-Extended-Reality

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My GitHub Profile</title>

<style>
    /* ===== Animated Cyberpunk Gradient Background ===== */
    body {
        margin: 0;
        padding: 40px;
        font-family: 'Segoe UI', Arial, sans-serif;
        color: #e3e3e3;

        background: linear-gradient(135deg, #0a0014, #1b0034, #001b29, #24001f);
        background-size: 400% 400%;
        animation: neonFlow 12s ease infinite;
    }

    @keyframes neonFlow {
        0% { background-position: 0% 50%; }
        50% { background-position: 100% 50%; }
        100% { background-position: 0% 50%; }
    }

    /* ===== Section Title Styling (Simple + Neon Glow) ===== */
    h2 {
        margin-top: 30px;
        font-size: 26px;
        color: #ff00cc;
        text-shadow: 0 0 10px #ff00cc;
        border-left: 4px solid #ff00cc;
        padding-left: 10px;
    }

    p {
        font-size: 15px;
        line-height: 1.6;
        color: #d9d9ff;
        max-width: 700px;
    }

    /* ===== Badges (Simple but Neon) ===== */
    .badge {
        display: inline-block;
        margin: 6px 8px 0 0;
        padding: 8px 14px;
        border-radius: 8px;
        font-size: 14px;
        font-weight: bold;
        color: white;
    }

    .cpp {
        background: #007bff;
        box-shadow: 0 0 10px #4da3ff;
    }
    .py {
        background: #ffb000;
        color: #222;
        box-shadow: 0 0 10px #ffd95a;
    }

    /* ===== Quote Box (Simple + Neon Border) ===== */
    .quote-box {
        margin-top: 25px;
        padding: 20px;
        background: rgba(0, 0, 0, 0.3);
        border-left: 4px solid #ff44aa;
        border-radius: 8px;
        box-shadow: 0 0 12px #ff44aa;
        font-style: italic;
        max-width: 750px;
    }

    .author {
        text-align: right;
        margin-top: 10px;
        color: #ff66c4;
        font-weight: bold;
        text-shadow: 0 0 8px #ff66c4;
    }
</style>
</head>

<body>

    <h2>👋 About Me</h2>
    <p>I'm currently learning HCI (Human–Computer Interaction).</p>
    <p>I’m a Computer Engineering student who loves coding and exploring new technologies.</p>

    <h2>💻 Tech Stack</h2>
    <span class="badge cpp">C++</span>
    <span class="badge py">Python</span>

    <h2>🔥 Random Dev Quote</h2>
    <div class="quote-box">
        “The complexity of software is an essential property, not an accidental one.
        Hence descriptions of a software entity that abstract away its complexity
        often abstract away its essence.”
        <div class="author">— Fred Brooks</div>
    </div>

</body>
</html>
