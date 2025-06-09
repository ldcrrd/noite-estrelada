<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Nossa Eterna Memória</title>
<style>
  /* Fundo noite estrelada */
  body {
    margin: 0;
    background: radial-gradient(ellipse at bottom, #1b2735 0%, #090a0f 100%);
    height: 100vh;
    overflow: hidden;
    color: #fff;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }

  /* Estrelas */
  #stars {
    position: fixed;
    width: 100%;
    height: 100%;
    background: transparent;
    pointer-events: none;
    z-index: 0;
  }

  .star {
    position: absolute;
    background: white;
    border-radius: 50%;
    opacity: 0.8;
    animation: twinkle 2s infinite alternate;
  }

  @keyframes twinkle {
    from {opacity: 0.2;}
    to {opacity: 1;}
  }

  /* Container principal */
  .container {
    position: relative;
    z-index: 10;
    max-width: 900px;
    margin: 40px auto;
    text-align: center;
  }

  h1 {
    fon
