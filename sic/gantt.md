```mermaid
gantt
    title Desarrollo E-commerce React
    dateFormat  YYYY-MM-DD
    axisFormat %d/%m
    
    section Setup Inicial
    Configuración del proyecto      :a1, 2024-11-18, 1d
    Config Ant Design y tema        :a2, after a1, 1d
    Config ESLint y rutas          :a3, after a2, 1d

    section Componentes Core
    Layout principal               :b1, after a3, 1d
    Componentes base              :b2, after b1, 2d

    section Carrito de Compras
    Integración API               :c1, after b2, 1d
    Implementación carrito        :c2, after c1, 2d
    Sincronización con API        :c3, after c2, 2d

    section Sistema de Pagos
    Integración STP              :d1, after c3, 1d
    Integración Conekta          :d2, after d1, 1d
    Integración PayPal           :d3, after d2, 1d

    section Facturación
    Sistema de facturación       :e1, after d3, 1d
    Comprobantes fiscales        :e2, after e1, 1d

    section Testing y Optimización
    Pruebas unitarias            :f1, after e2, 1d
    Pruebas de integración       :f2, after f1, 1d
    Optimización rendimiento     :f3, after f2, 2d
    Responsive design            :f4, after f3, 1d

    section Deployment
    Preparación producción       :g1, after f4, 1d
    Documentación               :g2, after g1, 1d
