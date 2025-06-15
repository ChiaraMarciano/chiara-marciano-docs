#  Documentazione tecnica

Questa sezione mostra in dettaglio come è costruita questa documentazione: struttura del sito, personalizzazioni, funzioni interattive e utilizzo di codice per migliorarla.

---

##  Struttura del progetto


## Configurazione `mkdocs.yml`

=== "YAML"

```yaml title="mkdocs.yml"
site_name: Documentazione di Chiara Marciano
theme:
  name: material
  features:
    - navigation.tabs
    - content.code.copy
```

##  Carosello HTML

=== "HTML"

```html title="gruppo-lettering.md"
<div style="display: flex;">
  <img src="one.jpg" style="height: 300px;">
</div>
```

##  Stile personalizzato

=== "CSS"

```css title="custom.css"
.carousel-img {
  transition: transform 0.3s ease;
}
```


=== "Bash"

```bash title="Terminale"
mkdocs serve
mkdocs gh-deploy
```
##  Aggiunta del font scaricabile

=== "HTML"

```html title="gruppo-lettering.md"
<p>
  <strong>Scarica il font Garibalds:</strong><br>
  <a href="../../files/Garibalds-Bold.otf" download>
    📥 Clicca qui per scaricare il file
  </a>
</p>
```

---

## Tag personalizzati in HTML

=== "HTML"

```html title="tags.md"
<div class="md-tags">
  <a href="anno-2025-2026/gruppo-lettering/" class="md-tag">lettering</a>
  <a href="anno-2025-2026/gruppo-transcultura/" class="md-tag">transcultura</a>
</div>
```

---

## Personalizzazione della nuvola di tag

=== "CSS"

```css title="custom.css"
.md-tags a.md-tag {
  font-size: 0.8rem;
  background-color: #e0f7fa;
  color: #00695c;
  border-radius: 20px;
  padding: 6px 12px;
  transition: background-color 0.3s ease;
}
```

---

## Centrare un'immagine rotonda

=== "HTML"

```html title="chi-sono.md"
<p align="center">
  <img src="images/chiara.png" alt="Chiara Marciano" width="250" style="border-radius: 50%;">
</p>
```


---
## Collegare una parola a un link esterno

=== "Markdown"

```markdown title="gruppo-transcultura.md"
Il progetto è ispirato a [Humanae](https://www.angelicadass.com/humanae/),  
un’indagine visiva sull’identità e la pelle.
```

---






