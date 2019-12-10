# webcam_point_features
Detection of ORB features from online webcam imges.
EJERCICIO 1.3

+ Hacemos Fork del programa cedido por BetaRobots.

+ Hacemos la compilación y creamos el ejecutable -Mkdir build -.../BUILD/CMAKE .. -.../BUILD/MAKE

+ Una vez ejecutado y ver que funciona correctamente empezamos hacer variaciones en el programa.

+ Podemos variar el número de puntos;
  
  const unsigned int MIN_NUM_FEATURES = 610; //minimum number of point fetaures
  
+ Variamos el color de los puntos;

    cv::drawKeypoints( image, point_set, image, 0, cv::DrawMatchesFlags::DEFAULT );


  
