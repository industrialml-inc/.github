# IndustrialML Inc

We're a company that helps make factories smarter. We make it easier for anyone involved in production, from the factory line to the back office, to have a complete picture of what's going on your production facilities. We work with you to create a full view of your operation, integrating PLCs, sensors and other live telemetry, with ERP and MES information. We can deliver customized alerts via multiple channels (web, mobile devices, email, Slack, SMS) with the right guidance on procedures, we can provide video feeds at key places on the line (which may also be fed to machine learning pipelines), and we can capture audio communications between line workers and transcribe the information automatically. With dashboards, user-customizable reports, and a mobile solution for operational procedure validation, our product takes a holistic view of production and worker training.

## Our technologies

Our web application is built in Elixir, using Phoenix.

We run a small gateway device in each factory with custom Elixir-based firmware to capture data from PLCs and sensors.

We also have custom code to integrate PoE cameras into a pipeline that can be used for both streaming video and Machine Learning proesses, mainly written in C++ and Python, with some plans to experiment with moving more of that into an Elixir-based pipeline.

We also have a solution built on the Membrane framework to capture audio communications between factory workers, transcribe that information, and bring it into the same integrated data view that allows operations managers to correlate plant conditions with chatter about incident management.
