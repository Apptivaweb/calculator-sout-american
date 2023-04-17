# Calculator Football Commebol South American JS - HTML 2023
South American Ranking Calculator  Javascript  - Html

Script de una calculadora para predicciones de las Eliminatorias Sudamericanas con ordenamiento en Javascript. Manipulación del DOM. Método Order and Render HTML

Algoritmo de ordenamiento en Javascript Vanilla
<img
  src="https://apptivaweb.com/img/post/axiosjs-una-libreria-de-promesas.jpg"
  alt="Alt text"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">

public function image(){
        $webp  =   new Imagick(public_path() ."/img/imagen.jpg");

        $overlay = new Imagick(public_path() ."/img/foto.jpg");
        $overlay->resizeImage( 150, 150, Imagick::FILTER_LANCZOS, 1);        

        $x = 250 - $overlay->getImageWidth()/2;
        $y = 250 - $overlay->getImageHeight()/2;

        $webp->compositeImage($overlay, Imagick::COMPOSITE_DEFAULT, $x, $y);
        $webp->setImageFormat('webp');
        $webp->writeImage(public_path() ."/img/p.webp"); 
        $webp->destroy();
    }
