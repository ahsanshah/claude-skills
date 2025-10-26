# BTPPT Quick Start

Complete working example of creating a Billtrust-branded presentation.

## Step 1: HTML Slide Example

```html
<!DOCTYPE html>
<html>
<head>
  <style>
    body {
      width: 960px;
      height: 540px;
      background: linear-gradient(135deg, #4934BA 0%, #6B60E0 100%);
      display: flex;
      flex-direction: column;
      justify-content: center;
      padding-left: 60px;
      font-family: 'Aptos Display', 'Calibri', sans-serif;
    }
    h1 {
      color: white;
      font-size: 54pt;
      font-weight: bold;
      margin-bottom: 20px;
    }
    .subtitle {
      color: #E7EDED;
      font-size: 20pt;
    }
  </style>
</head>
<body>
  <h1>Your Presentation Title</h1>
  <p class="subtitle">Subtitle • Date</p>
</body>
</html>
```

## Step 2: Convert to PowerPoint

```javascript
const pptxgen = require("pptxgenjs");
const { html2pptx } = require("@ant/html2pptx");

const pptx = new pptxgen();
pptx.layout = "LAYOUT_16x9";

await html2pptx("slide.html", pptx);
await pptx.writeFile("output.pptx");
```

## Step 3: Validate

```bash
python /mnt/skills/public/pptx/scripts/thumbnail.py output.pptx review --cols 4
```

## Key Colors

- Neon Green: #17FF9B (signature)
- Deep Purple: #4934BA (primary)
- Dark Teal: #001820 (text)

## More Examples

See Analytics_AI_EY_Content_Compressed.pptx for real-world Billtrust presentations.
