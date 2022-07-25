# figma-designtoken-test

npx token-transformer data/tokens.json output.json

The tokens we store on GitHub is the raw source of truth for the plugin. Meaning, it still contains aliases and any math you might have used. Tools such as Style Dictionary can't work with math, though.

So we need a way to transform our tokens to something Style Dictionary can read.

We need to install Token Transformer that can convert the data. Install by running npm install token-transformer.

You can then use it to generate tokens to a JSON that is readable by Style Dictionary, without any aliases, without any math.

run npx token-transformer data/tokens.json output.json

then run style-dictionary buildCreat
