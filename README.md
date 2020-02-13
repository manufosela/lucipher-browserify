# LUCipher-browserify

Browserify node package LUCipher

# Use

In your HTML insert script

```code
<script type="text/javascript" src="lucipher-browserify.min.js"></script>
```

Use LUCipher javascript class

```code
  const LUC = new LUCipher('mipassword', 'misalt');
  
  const code = LUC.cipher('Este es el texto a codificar');

  const decode = LUC.desCipher(code);
```