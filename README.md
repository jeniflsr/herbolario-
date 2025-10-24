<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Herbolario Natural</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            background-color: #E8F8F5; /* Verde muy claro (casi blanco) */
            color: #1A5237; /* Verde oscuro para el texto principal */
            margin: 0;
            padding: 20px;
        }
        header {
            background-color: #2ECC71; /* Verde esmeralda (contraste) */
            color: white;
            padding: 20px;
            text-align: center;
            border-radius: 8px;
            margin-bottom: 30px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1 {
            margin: 0;
            font-size: 2.5em;
        }
        .container {
            max-width: 1200px;
            margin: auto;
        }
        .planta {
            background-color: #D4EFDF; /* Verde menta claro */
            border: 2px solid #58D68D; /* Verde medio para el borde */
            border-radius: 10px;
            padding: 15px;
            margin-bottom: 25px;
            display: flex;
            gap: 20px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
        }
        .info {
            flex-grow: 3;
        }
        .imagen {
            flex-grow: 1;
            min-width: 150px;
            background-color: #A9DFBF; /* Verde pastel para el espacio de imagen */
            border: 1px dashed #2ECC71;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #1A5237;
            font-style: italic;
            text-align: center;
            border-radius: 5px;
            height: 150px; /* Tamaño fijo para la imagen */
            overflow: hidden;
        }
        .planta h2 {
            color: #0E6637; /* Verde oscuro fuerte */
            margin-top: 0;
            border-bottom: 2px solid #82E0AA;
            padding-bottom: 5px;
        }
        .planta p strong {
            color: #1A5237; /* Un verde más profundo para las etiquetas */
        }
    </style>
</head>
<body>

    <header>
        <h1>🌿 Mi Herbolario de Plantas Medicinales 🌿</h1>
        <p>Conoce las propiedades y beneficios de la naturaleza.</p>
    </header>

    <div class="container">
        <div class="planta">
            <div class="info">
                <h2>Manzanilla</h2>
                <p><strong>Nombre Científico:</strong> *Matricaria chamomilla*</p>
                <p><strong>Nombre Común:</strong> Camomila</p>
                <p><strong>Usos:</strong> Infusión para calmar el estómago y el sistema nervioso.</p>
                <p><strong>Beneficios:</strong> Antiinflamatoria, digestiva, sedante suave. Ayuda a conciliar el sueño.</p>
            </div>
            
                <img src="manzanilla.jpg" width="150" height="150">
        
        </div>

        <div class="planta">
            <div class="info">
                <h2>Menta</h2>
                <p><strong>Nombre Científico:</strong> *Mentha piperita*</p>
                <p><strong>Nombre Común:</strong> Menta piperita</p>
                <p><strong>Usos:</strong> Infusión para problemas digestivos, aromaterapia.</p>
                <p><strong>Beneficios:</strong> Antiespasmódica, alivia gases, refrescante, mejora la concentración.</p>
            </div>
            
           <img src="menta.jpg" width="100" height="100">
            
        </div>
        
        <div class="planta">
            <div class="info">
                <h2>Aloe Vera</h2>
                <p><strong>Nombre Científico:</strong> *Aloe barbadensis Miller*</p>
                <p><strong>Nombre Común:</strong> Sábila</p>
                <p><strong>Usos:</strong> Aplicación tópica para quemaduras y heridas, jugos para el sistema digestivo.</p>
                <p><strong>Beneficios:</strong> Cicatrizante, hidratante, antiinflamatoria, laxante suave.</p>
            </div>
          
        <img src="aloe.jpg" width="150" height="150">
          
        </div>

        <div class="planta">
            <div class="info">
                <h2>Lavanda</h2>
                <p><strong>Nombre Científico:</strong> *Lavandula angustifolia*</p>
                <p><strong>Nombre Común:</strong> Espliego</p>
                <p><strong>Usos:</strong> Aceite esencial para masajes, infusión, ambientador.</p>
                <p><strong>Beneficios:</strong> Relajante, ansiolítica, promueve el sueño, antiséptica.</p>
            </div>
      
            <img src="lavanda.jpg" width="1500" height="150">

        </div>
        
        <div class="planta">
            <div class="info">
                <h2>Jengibre</h2>
                <p><strong>Nombre Científico:</strong> *Zingiber officinale*</p>
                <p><strong>Nombre Común:</strong> Kion</p>
                <p><strong>Usos:</strong> Consumo fresco o seco en comidas e infusiones.</p>
                <p><strong>Beneficios:</strong> Antiinflamatorio, combate náuseas y vómitos, mejora la digestión.</p>
            </div>
            
                 <img src="gengibre.jpg" width="150" height="150">
            
        </div>

        <div class="planta">
            <div class="info">
                <h2>Valeriana</h2>
                <p><strong>Nombre Científico:</strong> *Valeriana officinalis*</p>
                <p><strong>Nombre Común:</strong> Hierba de los gatos</p>
                <p><strong>Usos:</strong> Extractos o cápsulas para el insomnio y la ansiedad.</p>
                <p><strong>Beneficios:</strong> Sedante potente, hipnótica, relaja el sistema nervioso.</p>
            </div>
        
              <img src="valeriana.jpg" width="150" height="150">
            
        </div>

        <div class="planta">
            <div class="info">
                <h2>Eucalipto</h2>
                <p><strong>Nombre Científico:</strong> *Eucalyptus globulus*</p>
                <p><strong>Nombre Común:</strong> Gomero azul</p>
                <p><strong>Usos:</strong> Inhalaciones para problemas respiratorios, aceite para masajes.</p>
                <p><strong>Beneficios:</strong> Expectorante, antiséptico, descongestionante nasal y bronquial.</p>
                        </div>
            
              <img src="eucalipto.jpg" width="150" height="150">
          
        </div>

        <div class="planta">
            <div class="info">
                <h2>Caléndula</h2>
                <p><strong>Nombre Científico:</strong> *Calendula officinalis*</p>
                <p><strong>Nombre Común:</strong> Botón de oro</p>
                <p><strong>Usos:</strong> Ungüentos, cremas e infusiones.</p>
                <p><strong>Beneficios:</strong> Cicatrizante, antiséptica, emoliente, útil para irritaciones de la piel.</p>
            </div>
            
              <img src="calendula.jpg" width="150" height="150">
            
        </div>
        
        <div class="planta">
            <div class="info">
                <h2>Tilo</h2>
                <p><strong>Nombre Científico:</strong> *Tilia platyphyllos*</p>
                <p><strong>Nombre Común:</strong> Flor de tilo</p>
                <p><strong>Usos:</strong> Infusión para el nerviosismo y el insomnio.</p>
                <p><strong>Beneficios:</strong> Ansiolítico, sedante, diaforético (induce la sudoración).</p>
            </div>
            
                <img src="tilo.jpg" width="150" height="150">
        
        </div>

        <div class="planta">
            <div class="info">
                <h2>Ruda</h2>
                <p><strong>Nombre Científico:</strong> *Ruta graveolens*</p>
                <p><strong>Nombre Común:</strong> Ruta</p>
                <p><strong>Usos:</strong> Tradicionalmente en infusiones (con precaución), usos externos.</p>
                <p><strong>Beneficios:</strong> Antiespasmódica, emenagoga (regula menstruación). **Usar con extrema precaución y dosis bajas.**</p>
            </div>
          
                 <img src="ruda.jpg" width="150" height="150">
            
        </div>

        <div class="planta">
            <div class="info">
                <h2>Diente de León</h2>
                <p><strong>Nombre Científico:</strong> *Taraxacum officinale*</p>
                <p><strong>Nombre Común:</strong> Achicoria amarga</p>
                <p><strong>Usos:</strong> Hojas en ensaladas, raíz en infusión.</p>
                <p><strong>Beneficios:</strong> Diurético natural, depurativo hepático y renal, rico en vitaminas.</p>
            </div>
          
              <img src="dientedeleon.jpg" width="250" height="250">
            
        </div>

        <div class="planta">
            <div class="info">
                <h2>Equinácea</h2>
                <p><strong>Nombre Científico:</strong> *Echinacea purpurea*</p>
                <p><strong>Nombre Común:</strong> Flor cónica púrpura</p>
                <p><strong>Usos:</strong> Infusiones, cápsulas o extractos.</p>
                <p><strong>Beneficios:</strong> Estimulante del sistema inmunológico, ayuda a prevenir resfriados.</p>
            </div>
            
                <img src="equinacea.jpg" width="150" height="150">
            
        </div>

        <div class="planta">
            <div class="info">
                <h2>Ortiga</h2>
                <p><strong>Nombre Científico:</strong> *Urtica dioica*</p>
                <p><strong>Nombre Común:</strong> Ortiga mayor</p>
                <p><strong>Usos:</strong> Infusiones, sopas, tónicos para el cabello.</p>
                <p><strong>Beneficios:</strong> Diurética, remineralizante, antiinflamatoria, útil para el reumatismo.</p>
            </div>
            
              <img src="ortiga.jpg" width="150" height="150">
            
        </div>

        <div class="planta">
            <div class="info">
                <h2>Romero</h2>
                <p><strong>Nombre Científico:</strong> *Salvia rosmarinus*</p>
                <p><strong>Nombre Común:</strong> Rosmarino</p>
                <p><strong>Usos:</strong> Condimento, infusión, aceite esencial, baños.</p>
                <p><strong>Beneficios:</strong> Estimulante, antioxidante, tónico capilar, mejora la memoria y concentración.</p>
            </div>
            
            <img src="romero1.jpg" width="150" height="150">
            
        </div>

        <div class="planta">
            <div class="info">
                <h2>Boldo</h2>
                <p><strong>Nombre Científico:</strong> *Peumus boldus*</p>
                <p><strong>Nombre Común:</strong> Boldea</p>
                <p><strong>Usos:</strong> Infusión de las hojas.</p>
                <p><strong>Beneficios:</strong> Digestivo, colerético (aumenta secreción biliar), protector hepático.</p>
            </div>
            
              <img src="boldo.jpg" width="150" height="150">
            
        </div>
        
    </div>

</body>
</html>
