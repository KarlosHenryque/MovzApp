# MovzApp

Aplicativo multiplataforma com frontend em React Native/Expo e backend em Java/Spring Boot.

## Estrutura

- `frontend/`: aplicativo para Android, iOS e web.
- `backend/`: API REST em Java com Spring Boot.

## Frontend

```bash
cd frontend
npm install
npm start
```

Comandos úteis: `npm run android`, `npm run ios` e `npm run web`.

## Backend

Requisitos: JDK 17+ e Maven 3.9+.

```bash
cd backend
mvn spring-boot:run
```

A API inicia em `http://localhost:8080` e possui o endpoint `GET /api/health`.

## Próximos módulos

As funcionalidades de negócio devem ser organizadas no backend em `controller`, `service`, `domain` e `repository`, mantendo o frontend separado por telas, componentes e serviços de API.

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```
