# Re-running after code state reset: recreate the final HTML file with upgrades

updated_html = """
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>HustleFlash - By Justice</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body { font-family: Arial, sans-serif; background: #0d1117; color: #f0f6fc; margin: 0; padding: 0; }
        header { background: #161b22; padding: 2rem; text-align: center; }
        h1 { font-size: 2.5rem; margin: 0; color: #58a6ff; }
        section { padding: 2rem; text-align: center; }
        .btns a {
            display: inline-block;
            margin: 1rem;
            padding: 1rem 2rem;
            background: #238636;
            color: white;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
        }
        .blog-post { margin-bottom: 1.5rem; background: #21262d; padding: 1rem; border-radius: 8px; }
        footer { background: #161b22; padding: 2rem; text-align: center; color: #8b949e; }
        a.telegram { color: #58a6ff; text-decoration: none; font-weight: bold; }
        a.download-btn {
            background: #f0b429;
            padding: 1rem 2rem;
            color: #000;
            font-weight: bold;
            text-decoration: none;
            border-radius: 8px;
        }
    </style>
</head>
<body>
    <header>
        <h1>HustleFlash</h1>
        <p>Money Tips, Affiliate Tricks, and Real Hustles</p>
        <p>By <strong>Justice</strong></p>
    </header>

    <section>
        <h2>Click and Earn</h2>
        <div class="btns">
            <a href="https://www.amazon.com/?tag=justiceflash2-20" target="_blank">Shop on Amazon</a>
            <a href="https://www.jumia.com.ng" target="_blank">Deals on Jumia</a>
            <a href="https://www.clickbank.com" target="_blank">Promote on ClickBank</a>
        </div>
    </section>

    <section>
        <h2>Latest Tips & Hustles</h2>
        <div class="blog-post">
            <h3>💡 Hustle Tip #1:</h3>
            <p>Use Amazon affiliate links in WhatsApp groups. Add short reviews and earn per click.</p>
        </div>
        <div class="blog-post">
            <h3>📲 Side Hustle Idea:</h3>
            <p>Use your phone to resell cheap digital services like airtime, followers, or designs.</p>
        </div>
    </section>

    <section>
        <h2>Download Our App</h2>
        <a class="download-btn" href="https://chat.openai.com/sandbox/mnt/data/hustleflash‑1.0.apk">Download for Android</a>
    </section>

    <section>
        <h2>Join Us</h2>
        <p>Follow us on Telegram: <a class="telegram" href="https://t.me/l_elastar" target="_blank">@l_elastar</a></p>
    </section>

    <section>
        <h2>Contact</h2>
        <p>WhatsApp: <strong>+2347034308620</strong> for more details</p>
    </section>

    <footer>
        &copy; 2025 HustleFlash. Built by Justice.
    </footer>
</body>
</html>
"""

# Save to file
final_path = "/mnt/data/index_updated.html"
with open(final_path, "w", encoding="utf-8") as f:
    f.write(updated_html)

final_path
