**Avida-ED-Eco — Web-based Ecology Extension of Avida-ED**

a.k.a. Avida-ED version 4

### **Short Description**

Avida-ED-Eco is the educational ecology extension of the Avida-ED digital evolution platform, providing a browser-based environment to explore experimental evolution and ecology with **digital organisms**. Avida-ED is an award-winning educational tool developed at Michigan State University that allows students to design and run real evolution experiments with evolving computer programs.

### **Purpose**

This repository contains the source code for the **Avida-ED ecological web interface**, enabling users to explore questions involving:

* **Resource dynamics** and **ecological interactions**.
* **Evolutionary processes** in ecosystems of digital organisms.
* **Population ecology experiments** involving competition, cooperation, and resource constraints.

It is built as the web-accessible interface for Avida-ED and is used in classroom and research settings to facilitate inquiry-based investigation of evolution and ecology. ([avida-ed.msu.edu])

### **Features**

* Browser-based application for running digital evolution experiments.
* Full ecology configuration support (e.g., limited resources, inflow rates).
* Educational user interface with real-time statistics and visualization.
* Integration with lesson plans and curricular materials. ([avida-ed.msu.edu][3])

### **Getting Started**

The Avida-ED-Eco web app is hosted online, accessible from the [Github pages link](https://welsberr.github.io/Avida-ED-Eco/), as well as links at the [Avida-ED main web site](https://avida-ed.msu.edu) and
the [Avida-ED mirror site at evo-edu.org](https://evo-edu.org/app4/).

### **Running Avida-ED-Eco Locally**

#### **Prerequisites**

To build and run the project locally:

- Install Git
- Install Python 3

Then follow these steps:

```bash
git clone https://github.com/Avida-ED/Avida-ED-Eco.git
cd Avida-ED-Eco
python -m http.server 8000
```

#### **Usage**

Once launched locally or deployed:

1. Open your browser at `http://localhost:8000`.
2. Configure a new evolutionary ecology experiment.
3. Set resource inflow and resource depletion parameters.
4. Start the digital evolution run and observe ecological dynamics.

### **Documentation**

See the [Avida-ED](https://avida-ed.msu.edu) site for these:

* **User Manual**
* **Tutorials** 
* **Curriculum Resources**

### **Contributing**

We welcome contributions. Please see `CONTRIBUTING.md` for guidelines.

### **License**

This project is licensed under the **GNU GPL v3.0** because of the licensing of
the underlying Avida code.

---

