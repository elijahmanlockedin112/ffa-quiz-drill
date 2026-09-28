# FFA Quiz Drill

A private study app. The page is encrypted (AES-256-GCM, key from the password with PBKDF2-SHA256, 600,000 rounds), and so is the progress file on the `progress` branch. The book pages in `lib/` are encrypted with the same key. Nothing readable is stored in this repo.
