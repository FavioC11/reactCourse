Temario React — desde Angular
Módulo 1 — Fundamentos (tu "Angular básico")

JSX — qué es y por qué existe (vs templates de Angular)
Componentes funcionales — la función ES el componente
Props — equivalente a @Input()
Estado con useState — equivalente a señales/variables del componente
Eventos — onClick, onChange vs (click), (change)
Renderizado condicional — &&, ternario vs @if
Listas — .map() y el concepto de key vs @for con track
Estilos — inline, CSS Modules, className vs [class]


Módulo 2 — Pensando en React (el cambio mental clave)

Flujo de datos unidireccional — por qué no hay two-way binding nativo
Lifting state up — cómo comunicar componentes sin un servicio
Composición vs herencia — cómo React reemplaza lo que Angular hace con ng-content
Inmutabilidad — por qué nunca mutas el estado directamente
Re-render — cuándo y por qué React re-renderiza


Módulo 3 — Hooks esenciales

useState — a fondo (ya lo tienes dominado)
useEffect — equivalente a ngOnInit, ngOnDestroy, ngOnChanges
useRef — equivalente a @ViewChild
useMemo — equivalente a computed signals / pure pipes
useCallback — optimización de funciones entre renders
useContext — equivalente ligero a un Service sin DI


Módulo 4 — Patrones de componentes

Controlled vs uncontrolled components — forms en React vs FormControl
Custom hooks — equivalente a Services reutilizables
Compound components — patrón avanzado de composición
Render props — patrón para compartir lógica (menos común hoy)
Higher Order Components (HOC) — equivalente a directivas de atributo


Módulo 5 — Manejo de formularios

Formularios controlados con useState
React Hook Form — equivalente a Reactive Forms de Angular
Validación — Zod + React Hook Form
Formularios no controlados con useRef


Módulo 6 — Routing

React Router v6 — equivalente al Router de Angular
Rutas anidadas — equivalente a rutas hijas
Rutas dinámicas y params — useParams
Navegación programática — useNavigate vs Router.navigate()
Guards — cómo proteger rutas sin CanActivate
Lazy loading de rutas — equivalente a loadChildren


Módulo 7 — Manejo de estado global

Context API a fondo — cuándo es suficiente vs cuándo no
Zustand — la alternativa simple (más liviana que NgRx)
Redux Toolkit — el equivalente más cercano a NgRx
Comparativa — cuándo usar cada uno


Módulo 8 — Async y data fetching

useEffect para fetching — el patrón básico
Race conditions en useEffect — un bug clásico
TanStack Query (React Query) — equivalente a efectos NgRx + caché de HTTP
SWR — alternativa más ligera
Suspense y manejo de loading states


Módulo 9 — Performance

Cómo funciona el Virtual DOM y la reconciliación
React.memo — equivalente a ChangeDetectionStrategy.OnPush
useMemo y useCallback — cuándo ayudan y cuándo son overhead
Code splitting con lazy y Suspense
Profiler de React DevTools


Módulo 10 — Ecosistema y herramientas

Vite + React — setup moderno (equivalente a Angular CLI)
Next.js — SSR, SSG, App Router (no tiene equivalente directo en Angular)
Testing con Vitest + Testing Library — equivalente a Jest + TestBed
TypeScript en React — tipos de props, hooks, eventos
Storybook — desarrollo aislado de componentes


Módulo 11 — Patrones avanzados

useReducer — estado complejo local, mini-Redux
useImperativeHandle + forwardRef — exponer métodos al padre
Error Boundaries — manejo de errores en el árbol de componentes
Portals — renderizar fuera del árbol del DOM
Concurrent features — useTransition, useDeferredValue


Ruta recomendada para ti dado que vienes de Angular con NgRx y RxJS:
Módulos 1 → 2 → 3 → 5 → 6 → 7 (directo a Zustand o Redux Toolkit) → 9
El módulo 2 es el más importante — es donde Angular y React piensan diferente. No lo saltes.
¿Quieres que empecemos por algún módulo en específico?