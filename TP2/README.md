# TP2

El corpus movie_reviews de NLTK contiene 2.000 críticas de películas en inglés, recopiladas del sitio IMDb. Está dividido en 1.000 críticas positivas y 1.000 críticas negativas. Cada archivo incluye el texto completo de una reseña. Este corpus presenta un vocabulario variado, lenguaje opinativo y una distribución balanceada entre clases.

agarrar elc orpues, reviasr el orceso para segmeneter y tokenizar, entrenar un modelo de gensim y mostrar el embedding obtenido, probar teste de anañlogia, ver similirades dentre palabras con matriz, test de analogia de rain y raoiny y graficar los embadding con tecnidcas de proyeccion y redactar consulusiones

agarrar elc orpues, reviasr el orceso para segmeneter y tokenizar, entrenar un modelo de gensim y mostrar el embedding obtenido, probar teste de anañlogia, ver similirades dentre palabras con matriz, test de analogia de rain y raoiny y graficar los embadding con tecnidcas de proyeccion y redactar consulusiones

ChatGPT said:
Perfecto, Lucas. Vamos a seguir los pasos que muestra la consigna, usando el corpus de Reuters que ya cargaste. El flujo sería este:

✅ 1. Preprocesamiento del corpus
Segmentar, tokenizar, y limpiar los textos.

✅ 2. Entrenamiento del modelo Word2Vec con Gensim
Con los textos ya procesados.

✅ 3. Exploración del espacio de embeddings
Ver palabras similares (model.wv.most_similar()).

Calcular distancias y similitudes entre términos.

Probar tests de analogía (model.wv.most_similar(positive=[...], negative=[...])).

✅ 4. Visualización
Proyectar los embeddings a 2D (PCA o t-SNE) y graficar.

✅ 5. Redactar conclusiones
Sobre las similitudes observadas, analogías que funcionan o fallan, clusters, etc.