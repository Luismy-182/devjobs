# DevJobs 💼

Plataforma web para la publicación y gestión de empleos, desarrollada con Laravel. Permite a empresas publicar vacantes y a usuarios explorar oportunidades laborales mediante una interfaz clara y dinámica.

---

## 🚀 Tecnologías

- Laravel
- Livewire
- TailwindCSS
- Laravel Breeze
- Eloquent ORM
- MySQL

---

## ✨ Funcionalidades

- Autenticación de usuarios
- Gestión de roles (reclutador / usuario)
- Publicación de vacantes
- Edición y eliminación de ofertas
- Panel administrativo
- Visualización detallada de vacantes
- Interfaz dinámica con Livewire (sin recargas completas)

---

## 🧠 Arquitectura

- Patrón MVC (Laravel)
- Componentes dinámicos con Livewire
- ORM con Eloquent
- Manejo de autenticación con Laravel Breeze
---

## ⚙️ Instalación

```bash
git clone https://github.com/Luismy-182/devjobs-platform.git
cd devjobs
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
