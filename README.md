# TIPO DE PROBLEMA: CLASIFICACION


## DESCRIPCION:

Las características se calculan a partir de una imagen digitalizada
con aguja fina (PAAF) de una masa mamaria.
Los datos describen las características de los núcleos celulares presentes en
la imagen.

La idea es utilizar el aprendizaje de maquina para determinar si la masa
analizada es Benigna o Maligna.


## DATOS:

- id: number
- diagnosis: The diagnosis of breast tissues (M = malignant, B = benign)
- radius_mean: mean of distances from center to points on the perimeter
- texture_mean: standard deviation of gray-scale values
- perimeter_mean: mean size of the core tumor
- area_mean
- smoothness_mean: mean of local variation in radius lengths
- compactness_mean: mean of perimeter^2 / area - 1.0
- concavity_mean: mean of severity of concave portions of the contour
- concave points_mean: mean for number of concave portions of the contour
- symmetry_mean
- fractal_dimension_mean: mean for "coastline approximation" - 1
- radius_se: standard error for the mean of distances from center to points on the perimeter
- texture_se: standard error for standard deviation of gray-scale values
- perimeter_se
- area_se
- smoothness_se: standard error for local variation in radius lengths
- compactness_se: standard error for perimeter^2 / area - 1.0
- concavity_se: standard error for severity of concave portions of the contour
- concave points_se: standard error for number of concave portions of the contour
- symmetry_se
- fractal_dimension_se: standard error for "coastline approximation" - 1
- radius_worst: "worst" or largest mean value for mean of distances from center to points on the perimeter
- texture_worst: "worst" or largest mean value for standard deviation of gray-scale values
- perimeter_worst
- area_worst
- smoothness_worst: "worst" or largest mean value for local variation in radius lengths
- compactness_worst: "worst" or largest mean value for perimeter^2 / area - 1.0
- concavity_worst: "worst" or largest mean value for severity of concave portions of the contour
- concave points_worst: "worst" or largest mean value for number of concave portions of the contour
- symmetry_worst
- fractal_dimension_worst: "worst" or largest mean value for "coastline approximation" - 1

## DATOS DE SALIDA:
- Diagnosis (M = malignant, B = benign)