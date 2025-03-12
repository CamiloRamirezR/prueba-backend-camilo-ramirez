<<<<<<< HEAD
<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

  <p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/dm/@nestjs/common.svg" alt="NPM Downloads" /></a>
<a href="https://circleci.com/gh/nestjs/nest" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master" alt="CircleCI" /></a>
<a href="https://discord.gg/G7Qnnhy" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
<a href="https://opencollective.com/nest#backer" target="_blank"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>
<a href="https://opencollective.com/nest#sponsor" target="_blank"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
  <a href="https://paypal.me/kamilmysliwiec" target="_blank"><img src="https://img.shields.io/badge/Donate-PayPal-ff3f59.svg" alt="Donate us"/></a>
    <a href="https://opencollective.com/nest#sponsor"  target="_blank"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>
  <a href="https://twitter.com/nestframework" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow" alt="Follow us on Twitter"></a>
</p>
  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor)-->

## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Project setup

```bash
$ npm install
```

## Compile and run the project

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Run tests

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Deployment

When you're ready to deploy your NestJS application to production, there are some key steps you can take to ensure it runs as efficiently as possible. Check out the [deployment documentation](https://docs.nestjs.com/deployment) for more information.

If you are looking for a cloud-based platform to deploy your NestJS application, check out [Mau](https://mau.nestjs.com), our official platform for deploying NestJS applications on AWS. Mau makes deployment straightforward and fast, requiring just a few simple steps:

```bash
$ npm install -g mau
$ mau deploy
```

With Mau, you can deploy your application in just a few clicks, allowing you to focus on building features rather than managing infrastructure.

## Resources

Check out a few resources that may come in handy when working with NestJS:

- Visit the [NestJS Documentation](https://docs.nestjs.com) to learn more about the framework.
- For questions and support, please visit our [Discord channel](https://discord.gg/G7Qnnhy).
- To dive deeper and get more hands-on experience, check out our official video [courses](https://courses.nestjs.com/).
- Deploy your application to AWS with the help of [NestJS Mau](https://mau.nestjs.com) in just a few clicks.
- Visualize your application graph and interact with the NestJS application in real-time using [NestJS Devtools](https://devtools.nestjs.com).
- Need help with your project (part-time to full-time)? Check out our official [enterprise support](https://enterprise.nestjs.com).
- To stay in the loop and get updates, follow us on [X](https://x.com/nestframework) and [LinkedIn](https://linkedin.com/company/nestjs).
- Looking for a job, or have a job to offer? Check out our official [Jobs board](https://jobs.nestjs.com).

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [Kamil Myśliwiec](https://twitter.com/kammysliwiec)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

Nest is [MIT licensed](https://github.com/nestjs/nest/blob/master/LICENSE).
=======
# 📝 Prueba Técnica - Desarrollador Backend Semi-Senior

## ⚠️ Antes de comenzar

Por favor, **lee toda la prueba completa antes de empezar**. El tiempo estimado para completarla es de **2-3 horas**, pero puedes tomar hasta **24 horas** para entregarla. La entrega se realiza a través de un **Pull Request (PR)** en este repositorio.

## 🔥 Instrucciones Generales

1. **Haz un fork** de este repositorio en tu cuenta de GitHub.
2. Crea una nueva rama con tu nombre o un identificador único:
   ```bash
   git checkout -b tu-nombre
   ```
3. Desarrolla tu solución en la rama creada.
4. Una vez finalizado, sube tus cambios a tu repositorio y abre un **Pull Request (PR)** hacia este repositorio.
5. **Asegúrate de incluir una breve descripción en el PR** explicando tu enfoque y decisiones técnicas.
6. Puedes usar **IA o cualquier recurso** que consideres necesario, pero ten en cuenta que podrías ser requerido para sustentar tu solución.

## 📌 Requerimientos

### 1️⃣ Implementación de API en NestJS

- Crea un servicio en **NestJS** que exponga endpoints para manejar entidades en **PostgreSQL** usando el ORM de tu preferencia (TypeORM o Prisma).
- Debe incluir CRUD para una entidad llamada `Productos` con los siguientes campos:
  - `id` (UUID, PK)
  - `nombre` (string)
  - `precio` (decimal)
  - `stock` (entero)

### 2️⃣ Seguridad y Buenas Prácticas

- Implementa **validaciones** con DTOs en los endpoints.
- Manejo adecuado de **excepciones**.
- Configuración de variables de entorno con `.env`.

### 3️⃣ Pruebas Unitarias

- Escribe pruebas unitarias para al menos un servicio usando **Jest**.

### 4️⃣ Conocimientos en AWS (Opcional, suma puntos)

- Describe cómo desplegarías esta API en **AWS ECS + RDS**.
- Explica brevemente cómo manejarías secretos con **AWS Secrets Manager**.
- Opcionalmente, agrega un pequeño **Terraform** para crear el RDS.

### 5️⃣ CI/CD con GitHub Actions y Terraform (Opcional, suma puntos)

- Crea un workflow en **GitHub Actions** para ejecutar pruebas automáticamente en cada `push` o `PR`.
- Opcionalmente, agrega un paso en el pipeline para desplegar la API en AWS usando **Terraform**.

## ⏳ Tiempo Estimado

Queremos que tengas el tiempo suficiente para hacerlo bien, pero sin presionarte demasiado. Lo ideal es que puedas completarlo en unas **2-3 horas**, pero puedes tomar hasta **24 horas** para entregarlo.

## 📬 Entrega

- Haz un **Pull Request** con tu código.
- Asegúrate de que los endpoints sean funcionales.
- Si tienes comentarios o explicaciones, agrégalas en el `README.md` de tu fork.

---

¡Buena suerte y esperamos ver tu solución! 🚀
>>>>>>> 9a7ea99abf7877f85226f994287b86e9dd145bf4
