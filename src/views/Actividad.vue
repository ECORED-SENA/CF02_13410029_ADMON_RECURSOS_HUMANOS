<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    #Actividad                
      <Actividad :cuestionario="cuestionario" />

</template>

<script>
import Actividad from '@/components/actividad/Actividad'
export default {
  name: 'ActividadDidactica',
  components: { Actividad },
  data: () => ({
    cuestionario: {
      tema: 'Manejo de los residuos sólidos en la producción avícola.',
      titulo: 'Cuestionario',
      introduccion:
        'Lea cada enunciado y luego seleccione la respuesta correcta según corresponda.',
      barajarPreguntas: false,
      preguntas: [
        {
          id: 1,
          texto:
            '¿Cuál es la finalidad del proceso de selección del talento humano?',
          imagen: require('@/assets/curso/img1.png'),
          barajarRespuestas: false,
          opciones: [
            {
              id: 'a',
              texto: 'Realizar evaluaciones físicas.',
              esCorrecta: false,
            },
            { id: 'b', texto: 'Capacitar a los empleados.', esCorrecta: false },
            {
              id: 'c',
              texto: 'Escoger al mejor candidato para la organización.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Desarrollar políticas de recursos humanos.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 2,
          texto: '¿Qué se debe hacer antes de comenzar la entrevista inicial?',
          imagen: require('@/assets/curso/img2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Realizar pruebas físicas.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Determinar las preguntas para el solicitante.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Revisar el historial médico del candidato.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Realizar la contratación.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 3,
          texto:
            '¿Cuál es una técnica recomendada durante la entrevista inicial?',
          imagen: require('@/assets/curso/img3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Realizar la entrevista en un ambiente ruidoso.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Dedicar poca atención al aspirante.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Observar la forma de hablar y comportamiento del entrevistado.',
              esCorrecta: true,
            },
            { id: 'd', texto: 'No hacer preguntas.', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 4,
          texto:
            '¿Qué tipo de pruebas se utilizan para evaluar las capacidades de los candidatos?',
          imagen: require('@/assets/curso/img4.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Pruebas físicas solamente.', esCorrecta: false },
            {
              id: 'b',
              texto:
                'Pruebas de personalidad, aptitud, conocimiento y muestreo de trabajo.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Entrevistas grupales únicamente.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Solo exámenes de laboratorio.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 5,
          texto: '¿Cuál es la última etapa del proceso de selección?',
          imagen: require('@/assets/curso/img1.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Pruebas.', esCorrecta: false },
            { id: 'b', texto: 'Entrevista inicial.', esCorrecta: false },
            { id: 'c', texto: 'Reclutamiento.', esCorrecta: false },
            { id: 'd', texto: 'Vinculación y contratación.', esCorrecta: true },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 6,
          texto:
            '¿Qué etapa del proceso de selección incluye la verificación de la información proporcionada por el candidato?',
          imagen: require('@/assets/curso/img2.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Entrevista inicial.', esCorrecta: false },
            { id: 'b', texto: 'Pruebas.', esCorrecta: false },
            {
              id: 'c',
              texto: 'Investigación de antecedentes.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Vinculación y contratación.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 7,
          texto:
            '¿Qué se busca en la etapa de análisis de necesidades del proceso de selección?',
          imagen: require('@/assets/curso/img3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Realizar entrevistas grupales.',
              esCorrecta: false,
            },
            { id: 'b', texto: 'Realizar exámenes médicos.', esCorrecta: false },
            {
              id: 'c',
              texto: 'Realizar estudios en los puestos de trabajo.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Contratar directamente a los candidatos.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 8,
          texto: '¿Qué es el reclutamiento externo?',
          imagen: require('@/assets/curso/img4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Convocatorias internas dentro de la organización.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Anuncios en avisos clasificados y redes sociales.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Recomendaciones de los líderes de la empresa.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Recolección de hojas de vida internamente.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 9,
          texto:
            '¿Cuál de las siguientes no es una política de gerencia del talento humano mencionada en el texto?',
          imagen: require('@/assets/curso/img1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Política de provisión del talento humano.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Políticas de desarrollo del personal.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Políticas de mantenimiento del equipo.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Políticas de expansión internacional.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 10,
          texto:
            '¿Qué se debe evaluar en los exámenes físicos del proceso de selección?',
          imagen: require('@/assets/curso/img2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'El estado de salud del aspirante.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'La capacidad de liderazgo del aspirante.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Las habilidades técnicas del aspirante.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'La experiencia laboral del aspirante.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
      ],
      mensaje_final_aprobado: '¡Excelente! Ha superado la actividad.',
      mensaje_final_reprobado:
        'Le recomendamos volver a revisar el componente formativo e intentar nuevamente la actividad didáctica.',
    },
  }),
  computed: {},
  methods: {},
}
</script>
