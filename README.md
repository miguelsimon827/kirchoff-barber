cat <<'EOF' > index.html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kirchoff - Peluquería Unisex</title>
    <style>
        :root { --primary: #2c3e50; --accent: #d35400; --light: #ecf0f1; }
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
        body { background-color: var(--light); color: #333; line-height: 1.6; }
        
        /* Navegación */
        nav { background-color: var(--primary); padding: 1rem 5%; position: fixed; width: 100%; top: 0; z-index: 1000; display: flex; justify-content: space-between; align-items: center;
