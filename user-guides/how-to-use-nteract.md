# How to use nteract

Interactive notebooks are a great tool for data scientists looking to document their code, experiment with models, generate visualizations, and prototype code. The most popular interactive notebook format in the data science ecosystem is the Jupyter notebook format.

### Setting up the nteract desktop application

The fastest way to get started with nteract is to download the desktop application to your machine. You can download the installer for your operating system on the [nteract homepage](https://nteract.io/desktop).

### Setting up the nteract web application

In addition to using nteract on the desktop, you can also use nteract within your web browser. 

### How to create a new notebook

Depending on your preference, you can create a new notebook in nteract in multiple ways.

If you're comfortable with the command line, you can use the `nteract` command to create or open a notebook from the command line.

Altneratively, you can open a notebook by either double clicking on the notebook file anywhere on your machine or selecting File > Open from the nteract menubar.

### Writing code in interactive notebooks

Now that we've got the nteract application installed, we can create our first notebook. New notbooks in nteract launch with a an empty code cell. You can use this code cell to write code that can be executed. Code must be written in the language of the kernel that you are connected to in order to execute. For example, the example below shows Python 3 code exeucting within an interactive notebook.

### Writing documentation in interactive notebooks

In addition to code cells, you can also create textual cells that can provide documentation and narrative for your code. These textual cells are formatted using the [Markdown formatting language](https://daringfireball.net/projects/markdown/). There are two ways to create a new Markdown cell in the nteract application. You can hover over the space after a cell and click the Markdown icon (it resembles an M with a down arrow next to it). Alternatively, you can select Edit > Insert Text Cell Below from the menubar.

Once the new Markdown cell has been created, you can double click to edit the Markdown cell and write your formatted text content.

### Organizing cells within a notebook

Like any written document, the organization of the content matters. nteract allows you to rearrange the cells within a notebook using drag-and-drop. You can click on the left hand side of a cell and drag it to the desired position.

### Speed things up with keyboard shortcuts

As you use notebooks more and more, you'll probably want to start taking advantage of some of the keyboard shortcuts that are provided within nteract. You can view a full list of these keyboard shortcuts, and how they compare to those provided within the JupyterLab and classic Jupyter front ends [here](https://docs.nteract.io/#/desktop/shortcut-keys).

### Rendering rich media in interactive notebooks

One of the most powerful features of notebooks is the ability to render rich media, like images and maps, within the notebook. Let's try this out by creating a notebook that renders an SVG image within the notebook.

The nteract application also contains some special renders for rich media. For example, GeoJSON data can be rendered in a visual using the [Leaflet](https://leafletjs.com/) open source library. 

### Creating visualizations with the nteract Data Explorer

The nteract Data Explorer is a built-in tool for visualizing pandas DataFrames within a notebook. Let's try this out with some publicly available data from the 

At this point, you're hopefully excited about all the notebooks you can create using nteract. You can view some of the example notebooks to view the possibilities that are available to you with nteract. You can open the example notebooks by selecting File > Open Example Notebook from the nteract menubar.