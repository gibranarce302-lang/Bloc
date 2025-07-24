# Bloc
<!DOCTYPE html>
<html>
<head>
  <title>Hola Cirilo</title>
    <style>
        body {
              background-color: #f2f2f2;
                    font-family: sans-serif;
                          padding: 20px;
                              }
                                  h1 {
                                        color: #007bff;
                                            }
                                                textarea {
                                                      width: 100%;
                                                            height: 200px;
                                                                  font-size: 16px;
                                                                        padding: 10px;
                                                                              margin-top: 20px;
                                                                                  }
                                                                                    </style>
                                                                                    <link rel="manifest" href="manifest.json">
                                                                                    <script>
                                                                                      if ('serviceWorker' in navigator) {
                                                                                          navigator.serviceWorker.register('sw.js')
                                                                                              .then(reg => console.log("Service Worker registrado"))
                                                                                                  .catch(err => console.log("Error al registrar", err));
                                                                                                    }
                                                                                                    </script></head>
                                                                                                    <body>
                                                                                                      <h1>Hola Cirilo!</h1>
                                                                                                        <p>Este es tu bloc de notas:</p>
                                                                                                          <textarea placeholder="Escribe aquí..."></textarea>
                                                                                                          </body>
        
                                                                                                  </html>