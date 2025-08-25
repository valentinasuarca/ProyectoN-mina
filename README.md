# Sistema de Gestión de Nómina

Sistema de nómina con interfaz moderna en Next.js y sistema legacy en Java para cálculos según legislación laboral colombiana.

## Instalación

### Aplicación Next.js
\`\`\`bash
npm install
npm run dev
\`\`\`
Abrir [http://localhost:3000](http://localhost:3000)

### Sistema Java
1. Abrir `login_basico` en NetBeans
2. Ejecutar `login.java`
3. Usuario: `mateo` / Contraseña: `1234`

## Características

- **Next.js 14** con TypeScript y Tailwind CSS
- **Sistema Java** con interfaz Swing
- **Cálculos automáticos** de nómina colombiana
- **Horas extras** y deducciones legales
- **Componentes UI** modernos con shadcn/ui

## Cálculos Incluidos

- Horas extras (125% - 250% según tipo)
- Deducciones: Salud (4%), Pensión (4%)
- Aportes patronales: Salud (8.5%), Pensión (12%)
- Auxilio de transporte y retención en la fuente

## Tecnologías

- **Frontend**: Next.js, TypeScript, Tailwind CSS
- **Backend Legacy**: Java, Swing, NetBeans
- **Componentes**: shadcn/ui, Radix UI

## Estructura

\`\`\`
proyecto-nomina/
├── app/                     # App Router de Next.js
│   ├── globals.css         # Estilos globales
│   └── layout.tsx          # Layout principal
├── components/             # Componentes React
│   ├── ui/                # Componentes shadcn/ui
│   └── theme-provider.tsx # Proveedor de temas
├── hooks/                 # Custom hooks
├── lib/                   # Utilidades
├── public/                # Archivos estáticos
├── login_basico/          # Sistema Java Legacy
│   ├── src/              # Código fuente Java
│   │   ├── login.java    # Sistema de autenticación
│   │   └── panel_control.java # Panel principal
│   └── nbproject/        # Configuración NetBeans
└── package.json          # Dependencias Node.js
\`\`\`

## Licencia

MIT License
