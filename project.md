---
layout: projects
title: "Projects"
groups:
  - name: "JavaScript · Data Science · ML on the Web"
    projects:
      - name: "Danfo.js"
        description: "Open-source JavaScript library providing high-performance, Pandas-like data structures for manipulating and processing structured data in the browser and Node.js. \n\nCo-created the project and contributed to the core dataframe data structure and it operations, plus the general architecture and design of the library"
        url: "https://github.com/javascriptdata/danfojs"
        image: "/assets/images/projects/danfojs2.png"
        stars: "5.k"
        contrib: false
        tags: ["javascript", "typescript", "data-science", "pandas"]
        links:
          - label: "GitHub"
            url: "https://github.com/javascriptdata/danfojs"
          - label: "Docs"
            url: "https://danfo.jsdata.org/"

      - name: "Dnotebook"
        description: "An interactive JavaScript notebook environment - think Jupyter but for the browser. \n\nI impemented the core notebook data model, cell execution logic etc."
        url: "https://github.com/javascriptdata/dnotebook"
        image: "/assets/images/projects/dnotebook.avif"
        stars: "153"
        contrib: false
        tags: ["javascript", "notebook", "data-science", "ml"]
        links:
          - label: "GitHub"
            url: "https://github.com/javascriptdata/dnotebook"
          - label: "Docs"
            url: "https://dnotebook.jsdata.org/"

      - name: "scikit.js"
        description: "A TypeScript port of scikit-learn for JS environments (browser, Node.js), powered by TensorFlow.js. \n\nContributed to project planning, the initial kickstart, and model saving implementation."
        url: "https://github.com/javascriptdata/scikit.js"
        image: "/assets/images/projects/scikitjs.png"
        stars: "145"
        contrib: false
        tags: ["typescript", "machine-learning", "scikit-learn", "tensorflow.js"]
        links:
          - label: "GitHub"
            url: "https://github.com/javascriptdata/scikit.js"
          - label: "Docs"
            url: "https://www.scikitjs.org/"

      - name: "Datacook"
        description: "Machine learning and data science library for JavaScript and TypeScript, powered by TensorFlow.js. \n\nContributed feature engineering utilities and preprocessing pipelines — a building block for training and deploying ML models entirely in-browser or on Node."
        url: "https://github.com/imgcook/datacook"
        image: "/assets/images/projects/datacook.png"
        stars: "44"
        contrib: true
        tags: ["typescript", "machine-learning", "tensorflow.js", "data-science"]
        links:
          - label: "GitHub"
            url: "https://github.com/imgcook/datacook"
          - label: "Docs"
            url: "https://imgcook.github.io/datacook"

  - name: "Open Data · Publishing Systems"
    projects:
      - name: "CKAN"
        description: "The world's leading open-source data portal platform — used by governments and organisations globally to publish and share datasets. \n\nContributed to adding new features, python 2 to 3 migration, bug fixes, documentation and creating varieties of extensions to improve data publishing workflows."
        url: "https://github.com/ckan/ckan"
        image: "/assets/images/projects/ckan.png"
        stars: "4.4k"
        contrib: true
        tags: ["python", "open-data", "flask", "postgresql", "redis"]
        links:
          - label: "GitHub"
            url: "https://github.com/ckan/ckan"
          - label: "Docs"
            url: "https://docs.ckan.org/"

      - name: "PortalJS"
        description: "A modern JavaScript/React framework built on Next.js for rapidly building rich, feature-complete open data portals and publishing systems. Natively supports CKAN, GitHub, Frictionless Data Packages, and more. \n\nHelped with the initial project kickstart and idea consolidation, and contributed to integrating the framework into various data portals."
        url: "https://github.com/datopian/portaljs"
        image: "/assets/images/projects/portaljs.png"
        stars: "2.3k"
        contrib: true
        tags: ["javascript", "react", "next.js", "open-data", "data-portal"]
        links:
          - label: "GitHub"
            url: "https://github.com/datopian/portaljs"
          - label: "Docs"
            url: "https://www.portaljs.com"

  - name: "Systems · Infrastructure · Machine Learning"
    projects:
      - name: "postgres-redis"
        description: "A Postgres extension written in Rust that hooks into the executor and replication pipeline to track updates on a chosen table column and mirror those values into Redis in real time. A deep dive into Postgres internals — shared memory, hooks, and the extension API."
        url: "https://github.com/systemEng-Learning/postgres-redis"
        image: "/assets/images/projects/postgres-redis.png"
        contrib: false
        tags: ["rust", "postgres", "redis", "systems"]
        links:
          - label: "GitHub"
            url: "https://github.com/systemEng-Learning/postgres-redis"
          - label: "Article"
            url: "/database/postgres-redis-extension-in-rust/"

      - name: "Firecracker Job Runner"
        description: "A minimal VM-based job runner that uses Firecracker micro-VMs to securely isolate and execute arbitrary user scripts. Each job gets its own ephemeral Linux VM with a mounted filesystem. Covers networking, Linux kernel images, root filesystems, and the Firecracker API end-to-end."
        url: "https://github.com/steveoni/microvm"
        image: "/assets/images/projects/microvm.png"
        contrib: false
        tags: ["go", "firecracker", "linux", "microvm"]
        links:
          - label: "GitHub"
            url: "https://github.com/steveoni/microvm"
          - label: "Article"
            url: "/microvm/notes-on-simple-vm-bases-job-runner/"

      - name: "go-ml-deployment"
        description: "Lightweight Go runtime for deploying and serving scikit-learn models exported as ONNX. Implements the ONNX graph execution engine from scratch in Go. Built for production-grade ML inference without a Python runtime dependency."
        url: "https://github.com/systemEng-Learning/go-ml-deployment"
        image: "/assets/images/projects/goml.png"
        contrib: false
        tags: ["go", "machine-learning", "onnx", "scikit-learn", "inference"]
        links:
          - label: "GitHub"
            url: "https://github.com/systemEng-Learning/go-ml-deployment"

  - name: "Interfaces · Developer Tools"
    projects:
      - name: "kbar"
        description: "Fast, portable, and extensible ⌘K command-palette interface for React apps.\n\n Contributed to improving the performance of the core action search algorithm"
        url: "https://github.com/timc1/kbar"
        image: "/assets/images/projects/kbar.png"
        stars: "5.2k"
        contrib: true
        tags: ["react", "typescript", "command-palette", "accessibility"]
        links:
          - label: "GitHub"
            url: "https://github.com/timc1/kbar"
          - label: "Website"
            url: "https://kbar.vercel.app/"
---

Most of the projects listed here are open source, giving me the opportunity to explore and share knowledge with a community of people interested in similar topics. I have explored topics and ideas around data publishing and orchestration, data science on the web, networking, interfaces, browser and IDE extensions, system programming, and more.
