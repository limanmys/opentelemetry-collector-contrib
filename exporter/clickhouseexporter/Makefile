include ../../Makefile.Common

run:
	cd ../../cmd/otelcontribcol && GOOS=linux go build -o ../../local/otelcontribcol
	cd example && docker compose up -d
