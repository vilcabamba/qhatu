# qhatu

Aplicación de gestión de inscripción de expositores y reserva de stands para la 186 Feria de Loja.

## Requerimientos
- Ruby 2.1.4+ (lenguaje)
- Rails 4.2.0 (marco de trabajo)
- PostgreSQL 8+ (BDD)

## Despliegue

1. Instalar ruby y bundler (p. ej. utilizando rbenv)

  ```
qhatu:$ rbenv install 2.1.4 && gem install bundler
  ```
  
2. Instalar gemas (incluido rails) requeridas

  ```
qhatu:$ bundle install
  ```
  
3. Crear la base de datos y actualizar el archivo de credenciales. Existe un ejemplo en `config/database.example.yml` que utilizamos como base:

  ```
qhatu:$ cp config/database.example.yml config/database.yml
  ```
  
4. Revisar las variables de entorno requeridas por `config/secrets.yml`
