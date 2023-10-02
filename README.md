# Cloud
1. **Clona este repositorio:**

   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd nombre_del_directorio

2. **Crea y activa un entorno virtual:**
   ```bash
   pip install virtualenv
   virtualenv venv
   source venv/bin/activate
   
4. **Instala las dependencias desde el archivo requirements.txt:**
   ```bash
   pip install -r requirements.txt
  
3. **Ejecuta la spider pages:**
   ```bash
   cd crawler
   scrapy crawl pages -o test_urls.csv
