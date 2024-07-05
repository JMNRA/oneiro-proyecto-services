# oneiro-proyecto-services

Pasos previos para inicializar servicios

## Crear carpetas data y log

```
mkdir -p data log && chown -R 1000:1000 data log
```

## Usar ejemplo .env-ejemplo

```
cp .env-ejemplo .env
```

## Ejecutar docker compose

```
docker compose up 
```


