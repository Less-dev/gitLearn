<h2 align="center">Git Learn</h2>
<p align="center">
<img src="https://github.com/Less-dev/gitLearn/assets/166412593/e8549989-97a0-4596-a64a-4b12b8a8459a" width="150">
</p>
<h3 align="center">Una aplicación para aprender a usar git</h3>

<p align="center">
<img src="https://user-images.githubusercontent.com/74038190/212744287-14f66c13-5458-40dc-9244-8ff533fc8f4a.gif" width="1000">
</p>

1. [`CÓMO CONTRIBUIR`](#Contribuciones)  
   1.1 [Bifurque el proyecto](#configuración-del-proyecto)

   1.2 [Descargue el proyecto en su máquina local](#descargue-el-proyecto)

   1.3 [Manténgase actualizado con el repositorio principal](#manténgase-actualizado)

   1.3.1 [Agregue el repositorio remoto a su espacio de trabajo](#agregue-el-repositorio-remoto)

   1.3.2 [Actualice su espacio de trabajo](#actualice-su-espacio-de-trabajo)

   1.3.3 [Combine el repositorio remoto con su espacio de trabajo](#combine-el-repositorio-remoto-con-su-espacio-de-trabajo)

   1.4 [Contribuya](#contribuya)

   1.4.1 [Busque una issue](#busque-una-issue-o-problema)

   1.4.2 [Agregue los cambios](#agregue-los-cambios)

   1.4.3 [Describa los cambios](#Describa-los-cambios-realizados)

   1.4.4 [Envie los cambios a su repositorio](#pushee-los-cambios)

3. [`ESPECIFICACIONES TÉCNICAS`](#especificaciones-técnicas)

   2.1 [Arquitectura](#arquitectura)

   2.1.2 [Arquitectura de módulos](#-arquitectura-de-módulos-de-social-local-)

   2.1.2.1 [Diagrama de base de datos](#-Diagrama-de-base-de-datos-de-Social-Local-)

   2.2 [Tecnologias](#-tecnologías)

   2.3 [Vistas](#-Vistas)

<p align="center">

<img alt="GIF" src="https://user-images.githubusercontent.com/74038190/212281763-e6ecd7ef-c4aa-45b6-a97c-f33f6bb592bd.gif" width="60" height="60" style="float: left;">

</p>

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="1000" heigh="20">

# `Contribuciones`

## Configuración del proyecto
### Haga una bifurcación de el [proyecto ](https://github.com/compose-projects-android/SocialLocal) a su repositorio privado

# Descargue el proyecto
### Teniendo en cuenta que ya se tiene descargada la herramienta [git](https://git-scm.com/), abra su terminal y clone su repositorio:
```
git clone https://github.com/miUser/gitLearn
```

# Manténgase actualizado
### Antes de cualquier contribución sincronice el repositorio remoto con su espacio de trabajo

## Agregue el repositorio remoto
```
git remote add upstream https://github.com/Less-dev/gitLearn
```
## Actualice su espacio de trabajo
```
git fetch upstream
```
## Combine el repositorio remoto con su espacio de trabajo

```
git merge upstream/<name_your_branch>
```

# Contribuya
### Busque hacer contribuciones claras y concisas, adjuntando videos u imágenes a sus PR.

## Busque una issue o problema
#### En la sección de issues del [repositorio remoto](https://github.com/compose-projects-android/SocialLocal/issues) mire si encuentra algo acorde a su conocimiento intelectual y que se ajuste a sus tiempos, para ser desarrollada con éxito. Si desea crear una solicitud de cambio haga lo mismo.

![image](https://github.com/compose-projects-android/SocialLocal/assets/166412593/9d58d736-84c9-40fb-8b49-494b28507be5)

## Agregue los cambios
#### En su espacio de trabajo haga factibles los cambios realizados
```
git add .
```
## Describa los cambios realizados
#### A la hora de contribuir, es muy importante describir a detalle lo que se hizo, para que los demás desarrolladores tengan una buena idea de lo que usted desarrolló.

```
git commit -m "Cambios que se hicieron"
```

## Pushee los cambios
#### Finalmente envie los cambios realizados a su repositorio y haga una PR a el repositorio remoto principal.

```
git push -u origin <name_your_branch>
```

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

# `Especificaciones Técnicas`

- **UI/UX:** Diseño intuitivo con soporte para temas claros y oscuros para una mejor experiencia de usuario.
- **Pruebas:** Incluye pruebas unitarias, de integración y de UI para asegurar la calidad del software.

# Arquitectura
#### Nos esforzamos por mantener una arquitectura Model-View-ViewModel (MVVM)

![image](https://github.com/compose-projects-android/SocialLocal/assets/166412593/af919336-0dc0-4934-ae25-dcd0f056301e)

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<h3 align="center">🧑‍🏫 Arquitectura de módulos de Git Learn </h3>

//image pedient

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<h3 align="center">📈 Diagrama de base de datos de Git Learn </h3>

//image pendient

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<h2 align="center">🛠 Tecnologías</h2>
<p align="center">

  <a href="https://dagger.dev/hilt/">
    <img src="https://img.shields.io/badge/-Dagger_Hilt-4285F4?style=flat-square&logo=android&logoColor=white" width="120" height="30" />
  </a>

  <a href="https://developer.android.com/topic/libraries/architecture/viewmodel?hl=es-419">
    <img src="https://img.shields.io/badge/-ViewModel-000000?style=flat-square&logo=android&logoColor=white" width="120" height="30" />  
  </a>

  <a href="https://developer.android.com/develop/ui/compose?hl=es-419">
    <img src="https://img.shields.io/badge/-Jetpack_Compose-green?style=flat-square&logo=jetpackcompose&logoColor=black" width="160" height="30" />
  </a>

  <a href="https://developer.android.com/training/data-storage/room?hl=es-419">
    <img src="https://img.shields.io/badge/-Room-red?style=flat-square&logo=android&logoColor=white" width="80" height="30" />
  </a>

</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/74038190/212744287-14f66c13-5458-40dc-9244-8ff533fc8f4a.gif" width="1000">
</p>



<h3 align="center">🎨 Vistas</h3>

#### Adjunto PDF

//pdf pendient3


#### by: [Less](https://github.com/less-dev/)
