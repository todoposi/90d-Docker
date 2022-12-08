DOCKER COMPOSE
===

## START SERVICES BY DOCKER COMPOSE FILE

### SIN LOG
```
docker-compose up
```

### CON LOG
```
docker-compose up -d
```

## STOP SERVICES BY DOCKER COMPOSE FILE
```
docker-compose down
```

## EXEC FRONTEND
```
docker exec -it 90d-frontend /bin/sh
```

### VARIABLES DE ENTORNO DEL FRONTEND
```
echo ${REACT_APP_AXIOS_SERVER}
echo ${REACT_APP_API_URL}
echo ${REACT_APP_URL}
```

## EXEC BACKEND
```
docker exec -it 90d-backend /bin/sh
```

### VARIABLES DE ENTORNO DEL BACKEND
```
echo ${FRONT_HOST}
echo ${BACK_HOST}
```

## LOGIN ACCOUNT
```
admin@azuresampledirectory90d.onmicrosoft.com
Mn87be3i2#
```