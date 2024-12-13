# TA05-Manual-IA-ASIXA
#DeepCode

DeepCode és un sistema d'intel·ligència artificial dissenyat per analitzar i millorar codi font de manera automàtica. Utilitza tècniques d'aprenentatge profund i models d'anàlisi contextual per detectar errors, suggerir millores de rendiment i garantir la qualitat del codi.

## Característiques principals

- **Anàlisi automàtica:** Identifica errors comuns i problemes de seguretat en el codi.
- **Optimització de codi:** Suggeriments per a un codi més net i eficient.
- **Compatible amb diversos llenguatges:** Suporta llenguatges com Python, Java, JavaScript, C++, i molts més.
- **Integracions:** Compatible amb sistemes de control de versions com Git i eines de desenvolupament com Visual Studio Code.
- **Aprenentatge constant:** Actualitza les seves regles i capacitats mitjançant l'entrenament amb bases de dades de codi actualitzades.

## Instal·lació

1. **Prerequisits**
   - Python 3.8 o superior
   - Gestor de paquets com pip o npm (per a versions compatibles amb JS)
   - Connexió a Internet per descarregar els models

2. **Descarrega i instal·la**
   ```bash
   git clone https://github.com/usuari/deepcode.git
   cd deepcode
   pip install -r requirements.txt
   ```

## ÚS BÀSIC

1. **Executar l'anàlisi del codi**
   ```bash
   python deepcode.py --analyze path_al_teu_codi
   ```
   Aquest comando analitzarà el codi del directori especificat i generarà un informe amb suggeriments.

2. **Integració amb Git**
   ```bash
   python deepcode.py --git-integrate
   ```
   Això permet analitzar automàticament els canvis abans de fer un commit.

## Configuració

El fitxer `config.json` conté les opcions de configuració de DeepCode. Pots personalitzar-lo per definir regles específiques o excloure arxius/directoris de l'anàlisi.

Exemple de `config.json`:
```json
{
    "exclude": ["node_modules", "venv"],
    "languages": ["python", "javascript"],
    "rules": {
        "security": true,
        "performance": true,
        "style": false
    }
}
```

## Contribució

1. **Clona el repositori:**
   ```bash
   git clone https://github.com/usuari/deepcode.git
   ```
2. **Crea una branca:**
   ```bash
   git checkout -b nova_funcionalitat
   ```
3. **Fes canvis i puja la branca:**
   ```bash
   git push origin nova_funcionalitat
   ```
4. **Envia una Pull Request (PR)** per a la revisió.

## Preguntes fàctiques

Si tens dubtes o trobes problemes, pots obrir una issue al repositori o contactar amb l'equip a [support@deepcode.com](mailto:support@deepcode.com).

## Llicència

Aquest projecte està disponible sota la llicència MIT. Consulta el fitxer `LICENSE` per a més detalls.
