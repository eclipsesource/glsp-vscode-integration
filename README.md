# Eclipse GLSP VSCode Integration

# Workflow Diagram Example

The workflow diagram is a consistent example provided by all GLSP components. The example implements a simple flow chart diagram editor with different types of nodes and edges (see screenshot below). The example can be used to try out different GLSP features, as well as several available integrations with IDE platforms (Theia, VSCode, Eclipse, Standalone).
As the example is fully open source, you can also use it as a blueprint for a custom implementation of a GLSP diagram editor.
See [our project website](https://www.eclipse.org/glsp/documentation/#workflowoverview) for an overview of the workflow example and all components implementing it.

![Workflow Diagram](/documentation/vscode-diagram.gif)

## How to start the Workflow Diagram example?

First, you need to build the VSCode-Integration packages:

```
yarn install
```

And the GLSP Server (Which includes the Workflow Diagram Server example). See [`glsp-server`](https://github.com/eclipse-glsp/glsp-server#building) for instructions.

Once both the Server and the Client packages are built, you can start both:

- Server: in `examples/org.eclipse.glsp.example.workflow`, start `org.eclipse.glsp.example.workflow.launch.WorkflowServerLauncher.java` (Or use the included `Start_Workflow_Example_Server.launch` Launch Configuration from Eclipse).
- Client: Execute the "Workflow GLSP Example Extension" launch configuration, provided with this project

## Where to find the sources?

In addition to this repository, the related source code can be found here:

-   https://github.com/eclipse-glsp/glsp-server
-   https://github.com/eclipse-glsp/glsp-client

# More information

For more information, please visit the [Eclipse GLSP Umbrella repository](https://github.com/eclipse-glsp/glsp) and the [Eclipse GLSP Website](https://www.eclipse.org/glsp/). If you have questions, contact us on our [spectrum chat](https://spectrum.chat/glsp/) and have a look at our [communication and support options](https://www.eclipse.org/glsp/contact/).
