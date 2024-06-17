## Description // Descripción
- `en` This script translates the text from a Word document from one language to another using the Google Translate API. It reads a Word document, translates each paragraph using the Google Translator library, and saves the translated text to a new Word document. Please note that this script does not maintain the formatting of the original document.
- `es` Este script traduce el texto de un documento de Word de un idioma a otro utilizando la API de Google Translate. Lee un documento de Word, traduce cada párrafo utilizando la biblioteca Google Translator y guarda el texto traducido en un nuevo documento de Word. Por favor, tenga en cuenta que este script no mantiene el formato del documento original.

## Installation // Instalación
- `en` Install the required libraries using pip. 
- `es` Instale las bibliotecas requeridas utilizando pip. 
```
pip install python-docx deep-translator
```

## Usage // Uso
<ol>
  <li>
    <p>- <code>en</code> Replace '<code>path/to/your/input/document.docx</code>' with the path to your input Word document.<br>
    - <code>es</code> Reemplace '<code>path/to/your/input/document.docx</code>' con la ruta de su documento de Word de entrada.</p>
  </li>
  <li>
    <p>- <code>en</code> Replace '<code>path/to/your/output/document.docx</code>' with the path where you want to save the translated Word document.<br>
    - <code>es</code> Reemplace '<code>path/to/your/output/document.docx</code>' con la ruta donde desea guardar el documento de Word traducido.</p>
  </li>
  <li>
    <p>- <code>en</code> You can edit the source and target languages by modifying the <code>src_lang</code> and <code>dest_lang</code> parameters in the <code>translate_docx</code> function. For example, to translate from Spanish to English, use:<br>
    - <code>es</code> Puede editar los idiomas de origen y destino modificando los parámetros <code>src_lang</code> y <code>dest_lang</code> en la función <code>translate_docx</code>. Por ejemplo, para traducir de español a inglés, utilice:</p>
    <pre><code>translate_docx(input_file, output_file, src_lang='es', dest_lang='en')
    </code></pre>
  </li>
  <li>Run code</li>
</ol>

## Supported Languages // Idiomas soportados
| Code | Lenguaje | Code | Lenguaje | Code | Lenguaje | Code | Lenguaje | Code | Lenguaje |
|:---: |  :---:   |:---: |  :---:   |:---: |  :---:   |:---: |  :---:   |:---: |  :---:   |
| `af`   | *Afrikaans*           | `sq`   | *Albanian*            | `am`   | *Amharic*             | `ar`   | *Arabic*              | `hy`   | *Armenian*            | 
| `az`   | *Azerbaijani*         | `eu`   | *Basque*              | `be`   | *Belarusian*          | `bn`   | *Bengali*             | `bs`   | *Bosnian*             | 
| `bg`   | *Bulgarian*           | `ca`   | *Catalan*             | `ceb`  | *Cebuano*             | `ny`   | *Chichewa*            | `zh-cn`| *Chinese (Simplified)*|
| `zh-tw`| *Chinese (Traditional)*| `co`   | *Corsican*           | `hr`   | *Croatian*            | `cs`   | *Czech*               | `da`   | *Danish*              | 
| `nl`   | *Dutch*               | `en`   | *English*             | `eo`   | *Esperanto*           | `et`   | *Estonian*            | `tl`   | *Filipino*            | 
| `fi`   | *Finnish*             | `fr`   | *French*              | `fy`   | *Frisian*             | `gl`   | *Galician*            | `ka`   | *Georgian*            |
| `de`   | *German*              | `el`   | *Greek*               | `gu`   | *Gujarati*            | `ht`   | *Haitian Creole*      | `ha`   | *Hausa*               | 
| `haw`  | *Hawaiian*            | `iw`   | *Hebrew*              | `hi`   | *Hindi*               | `hmn`  | *Hmong*               | `hu`   | *Hungarian*           | 
| `is`   | *Icelandic*           | `ig`   | *Igbo*                | `id`   | *Indonesian*          | `ga`   | *Irish*               | `it`   | *Italian*             | 
| `ja`   | *Japanese*            | `jw`   | *Javanese*            | `kn`   | *Kannada*             | `kk`   | *Kazakh*              | `km`   | *Khmer*               | 
| `rw`   | *Kinyarwanda*         | `ko`   | *Korean*              | `ku`   | *Kurdish (Kurmanji)*  | `ky`   | *Kyrgyz*              | `lo`   | *Lao*                 | 
| `la`   | *Latin*               | `lv`   | *Latvian*             | `lt`   | *Lithuanian*          | `lb`   | *Luxembourgish*       | `mk`   | *Macedonian*          |
| `mg`   | *Malagasy*            | `ms`   | *Malay*               | `ml`   | *Malayalam*           | `mt`   | *Maltese*             | `mi`   | *Maori*               |
| `mr`   | *Marathi*             | `mn`   | *Mongolian*           | `my`   | *Myanmar (Burmese)*   | `ne`   | *Nepali*              | `no`   | *Norwegian*           | 
| `ps`   | *Pashto*              | `fa`   | *Persian*             | `pl`   | *Polish*              | `pt`   | *Portuguese*          | `pa`   | *Punjabi*             |
| `ro`   | *Romanian*            | `ru`   | *Russian*             | `sm`   | *Samoan*              | `gd`   | *Scots Gaelic*        | `sr`   | *Serbian*             | 
| `st`   | *Sesotho*             | `sn`   | *Shona*               | `sd`   | *Sindhi*              | `si`   | *Sinhala*             | `sk`   | *Slovak*              | 
| `sl`   | *Slovenian*           | `so`   | *Somali*              | `es`   | *Spanish*             | `su`   | *Sundanese*           | `sw`   | *Swahili*             |
| `sv`   | *Swedish*             | `tg`   | *Tajik*               | `ta`   | *Tamil*               | `te`   | *Telugu*              | `th`   | *Thai*                | 
| `tr`   | *Turkish*             | `uk`   | *Ukrainian*           | `ur`   | *Urdu*                | `ug`   | *Uyghur*              | `uz`   | *Uzbek*               | 
| `vi`   | *Vietnamese*          | `cy`   | *Welsh*               | `xh`   | *Xhosa*               | `yi`   | *Yiddish*             | `yo`   | *Yoruba*              |
| `zu`   | *Zulu*                |


## Note
- The script requires an internet connection to use the Google Translate API.
- Make sure to replace the input and output file paths with your own paths.
