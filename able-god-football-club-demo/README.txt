ABLE GOD FOOTBALL CLUB — WEBSITE DEMO

Files:
- index.html       Static website demo
- club-logo.jpg    Supplied Able God FC logo

Open index.html in a browser to preview.

The structure is intentionally Laravel-friendly:
- Each major section can later become a Blade partial.
- Fixtures/news/squad data can later come from Eloquent models.
- Navigation and content IDs are already separated into logical sections.
- No framework is required for this demo.

Suggested Laravel conversion:
resources/views/layouts/app.blade.php
resources/views/partials/navbar.blade.php
resources/views/home.blade.php
resources/views/partials/footer.blade.php

The fixture/news text is demo content and can be replaced with real club data.
