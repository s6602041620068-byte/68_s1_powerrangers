# Cyber Security

## Information
- Thammasat (BEW) 6602041620068
- Anupong (Art) 6602041620149
- Taksaya (Mint) 6602041610038  
- Phuwadet (Phu) 6602041620131
- Punyanan (Whan) 6602041630021

## Running a services
### Database
```
docker compose -f db.yaml up #monitoring
docker compose -f db.yaml up -d #background
```
### Admin
```
docker compose -f admin.yaml up #monitoring
docker compose -f admin.yaml up -d #background
```

### App 
```
docker compose -f app.yaml up #monitoring
docker compose -f app.yaml up -d #background
```

## Run all service 
```
docker-compose up #monotoring
docker-compose up -d #background 
```