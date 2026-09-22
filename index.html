import * as THREE from "three";

import {
    OrbitControls
} from "three/addons/controls/OrbitControls.js";


// =====================================================
// 💌 AQUÍ ESCRIBES TUS MENSAJES
// =====================================================

const cartas = [

    {
        titulo: "lindo pony 🌻",
        mensaje: "Eres tan linda como una pony que siempre me gusta estar junto a ti "
    },

    {
        titulo: "Una flor para ti 🌻",
        mensaje: "eres lo mas importante para mi y siempre quiero que estes bien y feliz"
    },

    {
        titulo: "dulce agnes 💛",
        mensaje: "Eres mi sol en los días nublados y mi alegría en los momentos difíciles"
    },

    {
        titulo: "Para alguien especial 🌻",
        mensaje: "desde lo poco que te llevo conociendo me has hecho sentir cosas que nunca habia sentido"
    },

    {
        titulo: "Mi flor favorita 🌻",
        mensaje: "siempre quedo impactado por tu forma de ser y la forma de tu pensar"
    },

    {
        titulo: "Un pequeño mensaje 💛",
        mensaje: "quiero que sepas que siempre voy a estar para ti pase lo que pase "
    },

    {
        titulo: "Un ramo para ti 💐",
        mensaje: "daria todo de mi por ti y seguiria siendo poco para lo que realmente mereces"
    },

    {
        titulo: "Otra carta 🌻",
        mensaje: "nunca vi a una persona de la forma en la que lo hago contigo"
    },

    {
        titulo: "mi mundo 💛",
        mensaje: "agnes , lo eres todo para mi"
    },

    {
        titulo: "Eres especial 🌻",
        mensaje: "eres la persona que me hace sentir vivo y me inspira a ser mejorcada dia"
    }

];


// =====================================================
// ESCENA
// =====================================================

const escena = new THREE.Scene();

escena.background =
    new THREE.Color(0x000000);


// =====================================================
// CÁMARA
// =====================================================

const camara =
    new THREE.PerspectiveCamera(
        65,
        window.innerWidth /
        window.innerHeight,
        0.1,
        1000
    );

camara.position.set(
    0,
    5,
    18
);


// =====================================================
// RENDER
// =====================================================

const renderer =
    new THREE.WebGLRenderer({
        antialias: true
    });

renderer.setSize(
    window.innerWidth,
    window.innerHeight
);

renderer.setPixelRatio(
    Math.min(
        window.devicePixelRatio,
        2
    )
);

document.body.appendChild(
    renderer.domElement
);


// =====================================================
// CONTROLES 3D
// =====================================================

const controles =
    new OrbitControls(
        camara,
        renderer.domElement
    );

controles.enableDamping = true;

controles.dampingFactor = .04;

controles.enablePan = false;

controles.minDistance = 6;

controles.maxDistance = 35;

controles.autoRotate = true;

controles.autoRotateSpeed = .15;


// =====================================================
// LUCES
// =====================================================

escena.add(
    new THREE.AmbientLight(
        0xffffcc,
        1.5
    )
);

const luz =
    new THREE.PointLight(
        0xffdf00,
        30,
        40
    );

luz.position.set(
    0,
    0,
    0
);

escena.add(luz);


// =====================================================
// ❤️ CORAZÓN CENTRAL
// =====================================================

function crearCorazon() {

    const forma =
        new THREE.Shape();

    forma.moveTo(
        0,
        -1.2
    );

    forma.bezierCurveTo(
        -2,
        -2.7,
        -3.2,
        .2,
        0,
        2.2
    );

    forma.bezierCurveTo(
        3.2,
        .2,
        2,
        -2.7,
        0,
        -1.2
    );


    const geometria =
        new THREE.ExtrudeGeometry(
            forma,
            {
                depth: .45,
                bevelEnabled: true,
                bevelSegments: 5,
                bevelSize: .08,
                bevelThickness: .08
            }
        );


    geometria.center();


    const material =
        new THREE.MeshStandardMaterial({

            color: 0xffff55,

            emissive: 0xffd500,

            emissiveIntensity: 2.2,

            roughness: .2,

            metalness: .1
        });


    const corazon =
        new THREE.Mesh(
            geometria,
            material
        );


    corazon.scale.set(
        1.15,
        1.15,
        1.15
    );


    corazon.rotation.x =
        Math.PI;


    return corazon;
}


const corazon =
    crearCorazon();
corazon.userData.interactivo = true;
corazon.userData.titulo = "Mi corazón para ti ❤️";
corazon.userData.mensaje = "agnes , ya tengo tiempo guardandome esto que siento por ti y crece cada dia que pasa , eres la persona mas pura y hermosa que conozco eres la persona que me hace estar en otro mundo cada vez que estoy a tu lado, cada momento junto a ti ,cada risa tuya era razon mas que suficiente para tratar de ser mejor. Eres una persona muy carismatica , y por experiencia alguien fuerte tambien.Estas palabras son muy pocas para expresarte todo lo que siento por ti , pero dejame decirte algo . TE AMO hiba a decir ,algo, pero mejor no la cago jajaja , pero es verdad que te amo , lo eres todo para mi";
escena.add(corazon);


// =====================================================
// ✨ HALOS DEL CORAZÓN
// =====================================================

for (
    let i = 0;
    i < 5;
    i++
) {

    const halo =
        new THREE.Mesh(

            new THREE.SphereGeometry(
                2.2 + i * .8,
                32,
                32
            ),

            new THREE.MeshBasicMaterial({

                color: 0xffe000,

                transparent: true,

                opacity:
                    .035 - i * .005

            })

        );

    escena.add(halo);
}


// =====================================================
// 💫 ANILLOS DE LUZ
// =====================================================

const anillos = [];

for (
    let i = 0;
    i < 4;
    i++
) {

    const geometria =
        new THREE.TorusGeometry(
            4 + i * 1.5,
            .015,
            8,
            180
        );


    const anillo =
        new THREE.Mesh(

            geometria,

            new THREE.MeshBasicMaterial({
                color: 0xffdf00,
                transparent: true,
                opacity: .55
            })

        );


    anillo.rotation.x =
        Math.PI / 2;

    anillo.rotation.z =
        i * .5;


    escena.add(
        anillo
    );

    anillos.push(
        anillo
    );
}


// =====================================================
// ⭐ ESTRELLAS
// =====================================================

const estrellas = [];

for (
    let i = 0;
    i < 650;
    i++
) {

    const tamaño =
        .025 +
        Math.random() * .08;


    const estrella =
        new THREE.Mesh(

            new THREE.SphereGeometry(
                tamaño,
                6,
                6
            ),

            new THREE.MeshBasicMaterial({
                color: 0xffff55
            })

        );


    const radio =
        9 +
        Math.random() * 25;


    const angulo =
        Math.random() *
        Math.PI * 2;


    estrella.position.set(

        Math.cos(angulo) *
        radio,

        (Math.random() - .5) *
        22,

        Math.sin(angulo) *
        radio

    );


    escena.add(
        estrella
    );

    estrellas.push(
        estrella
    );
}


// =====================================================
// ⭐ ESTRELLAS GRANDES
// =====================================================

for (
    let i = 0;
    i < 65;
    i++
) {

    const estrella =
        new THREE.Mesh(

            new THREE.SphereGeometry(
                .10 +
                Math.random() * .15,
                8,
                8
            ),

            new THREE.MeshBasicMaterial({
                color: 0xffff00
            })

        );


    const radio =
        8 +
        Math.random() * 17;


    const angulo =
        Math.random() *
        Math.PI * 2;


    estrella.position.set(

        Math.cos(angulo) *
        radio,

        (Math.random() - .5) *
        15,

        Math.sin(angulo) *
        radio

    );


    escena.add(
        estrella
    );

    estrellas.push(
        estrella
    );
}


// =====================================================
// 🌻 CREAR GIRASOL CON TALLO Y HOJAS
// =====================================================

function crearGirasol(numero) {

    const grupo =
        new THREE.Group();


    // -------------------------------
    // TALLO
    // -------------------------------

    const tallo =
        new THREE.Mesh(

            new THREE.CylinderGeometry(
                .055,
                .08,
                2.5,
                10
            ),

            new THREE.MeshStandardMaterial({
                color: 0x39751f,
                roughness: .8
            })

        );


    tallo.position.y =
        -1.25;


    grupo.add(
        tallo
    );


    // -------------------------------
    // HOJAS
    // -------------------------------

    for (
        let i = 0;
        i < 2;
        i++
    ) {

        const hoja =
            new THREE.Mesh(

                new THREE.SphereGeometry(
                    .32,
                    10,
                    10
                ),

                new THREE.MeshStandardMaterial({
                    color: 0x5b9d25
                })

            );


        hoja.scale.set(
            1.7,
            .35,
            .6
        );


        hoja.position.set(

            i === 0
                ? -.28
                : .28,

            -.9 -
            i * .55,

            0

        );


        hoja.rotation.z =
            i === 0
                ? -.45
                : .45;


        grupo.add(
            hoja
        );
    }


    // -------------------------------
    // CENTRO
    // -------------------------------

    const centro =
        new THREE.Mesh(

            new THREE.SphereGeometry(
                .36,
                16,
                16
            ),

            new THREE.MeshStandardMaterial({

                color: 0x593500,

                roughness: .8

            })

        );


    centro.position.y =
        .25;


    grupo.add(
        centro
    );


    // -------------------------------
    // PÉTALOS
    // -------------------------------

    for (
        let i = 0;
        i < 18;
        i++
    ) {

        const petalo =
            new THREE.Mesh(

                new THREE.SphereGeometry(
                    .23,
                    10,
                    10
                ),

                new THREE.MeshStandardMaterial({

                    color: 0xffd900,

                    emissive: 0x6b4e00,

                    emissiveIntensity: .5

                })

            );


        const angulo =
            i *
            Math.PI * 2 /
            18;


        petalo.position.set(

            Math.cos(angulo) *
            .47,

            .25 +
            Math.sin(angulo) *
            .47,

            0

        );


        petalo.scale.set(
            1,
            .55,
            1
        );


        grupo.add(
            petalo
        );
    }


    // -------------------------------
    // DATOS DE LA CARTA
    // -------------------------------

    grupo.userData.interactivo =
        true;

    grupo.userData.numero =
        numero;

    grupo.userData.titulo =
        cartas[
            numero - 1
        ].titulo;

    grupo.userData.mensaje =
        cartas[
            numero - 1
        ].mensaje;


    return grupo;
}


// =====================================================
// 🌻 FLORES ALREDEDOR DEL CORAZÓN
// =====================================================

const flores = [];

const posiciones = [

    [-5, 2.5, -2],
    [5, 2, -3],

    [-7, -1, 1],
    [7, -2, 2],

    [-3, -3.5, -5],
    [3, -3, -6],

    [-8, 3.5, -6],
    [8, 3, -7],

    [-4, 4, -8],
    [5, 4, -9]

];


for (
    let i = 0;
    i < posiciones.length;
    i++
) {

    const flor =
        crearGirasol(
            i + 1
        );


    flor.position.set(
        posiciones[i][0],
        posiciones[i][1],
        posiciones[i][2]
    );


    const escala =
        .8 +
        Math.random() * .65;


    flor.scale.set(
        escala,
        escala,
        escala
    );


    escena.add(
        flor
    );


    flores.push(
        flor
    );
}


// =====================================================
// 💐 RAMOS
// =====================================================

function crearRamo(numero) {

    const ramo =
        new THREE.Group();


    for (
        let i = 0;
        i < 4;
        i++
    ) {

        const flor =
            crearGirasol(
                numero
            );


        flor.scale.set(
            .5,
            .5,
            .5
        );


        flor.position.set(

            (i - 1.5) *
            .45,

            Math.abs(
                i - 1.5
            ) * .18,

            0

        );


        ramo.add(
            flor
        );
    }


    ramo.userData.interactivo =
        true;

    ramo.userData.numero =
        numero;

    ramo.userData.titulo =
        cartas[
            numero - 1
        ].titulo;

    ramo.userData.mensaje =
        cartas[
            numero - 1
        ].mensaje;


    return ramo;
}


const ramo1 =
    crearRamo(7);

ramo1.position.set(
    -9,
    1,
    -5
);

escena.add(
    ramo1
);

flores.push(
    ramo1
);


const ramo2 =
    crearRamo(8);

ramo2.position.set(
    9,
    1,
    -5
);

escena.add(
    ramo2
);

flores.push(
    ramo2
);


// =====================================================
// RAYCASTER
// =====================================================

const raycaster =
    new THREE.Raycaster();

const puntero =
    new THREE.Vector2();


function tocarFlor(event) {

    let x;
    let y;


    if (
        event.changedTouches
    ) {

        x =
            event.changedTouches[0]
                .clientX;

        y =
            event.changedTouches[0]
                .clientY;

    } else {

        x =
            event.clientX;

        y =
            event.clientY;
    }


    puntero.x =
        x /
        window.innerWidth *
        2 - 1;


    puntero.y =
        -(y /
        window.innerHeight *
        2 - 1);


    raycaster.setFromCamera(
        puntero,
        camara
    );


    const objetos =
    raycaster.intersectObjects(
        [corazon, ...flores],
        true
    );


    if (
        objetos.length === 0
    ) return;


    let objeto =
        objetos[0].object;


    while (
        objeto.parent &&
        !objeto.userData.interactivo
    ) {

        objeto =
            objeto.parent;
    }


    if (
        objeto.userData.interactivo
    ) {

        abrirCarta(
            objeto.userData.titulo,
            objeto.userData.mensaje
        );
    }
}


renderer.domElement.addEventListener(
    "click",
    tocarFlor
);


// =====================================================
// 💌 CARTA
// =====================================================

function abrirCarta(
    titulo,
    mensaje
) {

    document.getElementById(
        "tituloCarta"
    ).textContent =
        titulo;


    document.getElementById(
        "mensajeCarta"
    ).textContent =
        mensaje;


    document.getElementById(
        "fondoCarta"
    ).style.display =
        "flex";
}


document.getElementById(
    "cerrar"
).onclick = () => {

    document.getElementById(
        "fondoCarta"
    ).style.display =
        "none";
};


// =====================================================
// ANIMACIÓN
// =====================================================

const reloj =
    new THREE.Clock();


function animar() {

    requestAnimationFrame(
        animar
    );


    const tiempo =
        reloj.getElapsedTime();


    // ❤️ Corazón flotando

    corazon.position.y =
        Math.sin(
            tiempo * 1.5
        ) * .12;


    corazon.rotation.y =
        Math.sin(
            tiempo * .7
        ) * .08;


    // 🌻 Flores flotando

    flores.forEach(
        (flor, i) => {

            flor.position.y +=
                Math.sin(
                    tiempo * 1.2 + i
                ) * .0007;


            flor.rotation.z =
                Math.sin(
                    tiempo +
                    i
                ) * .04;

        }
    );


    // ⭐ Estrellas

    estrellas.forEach(
        (estrella, i) => {

            const brillo =
                1 +
                Math.sin(
                    tiempo * 2 +
                    i
                ) * .35;


            estrella.scale.set(
                brillo,
                brillo,
                brillo
            );
        }
    );


    // 💫 Anillos

    anillos.forEach(
        (anillo, i) => {

            anillo.rotation.z +=
                .0008 +
                i * .0003;

        }
    );


    controles.update();


    renderer.render(
        escena,
        camara
    );
}


animar();


// =====================================================
// 📱 PANTALLA
// =====================================================

window.addEventListener(
    "resize",
    () => {

        camara.aspect =
            window.innerWidth /
            window.innerHeight;


        camara.updateProjectionMatrix();


        renderer.setSize(
            window.innerWidth,
            window.innerHeight
        );
    }
);