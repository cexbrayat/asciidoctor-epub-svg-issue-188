To reproduce run:

    docker run -it -v $PWD:/documents/ asciidoctor/docker-asciidoctor:latest asciidoctor -b epub3 -r asciidoctor-epub3 -r asciidoctor-diagram test.adoc

Whereas it works with `asciidoctor-epub3@1.5.0.alpha.7`:

    docker run -it -v $PWD:/documents/ asciidoctor/docker-asciidoctor@sha256:b1268f852dfb276b2f5cefa52fdf3c2e62e86d54d264cea647ccd713c92a7e66 asciidoctor -b epub3 -r asciidoctor-epub3 -r asciidoctor-diagram test.adoc
