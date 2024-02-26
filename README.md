# helm_project
Helm Project Repository


</br> clustrer: contains the yaml file that creates the "slave" nodes and create cluster between them with the master.
      </br>nginx-volume: contains main html file of the nginx website.
      </br>values.yaml: contains values that permanently used in the project. In this case called by the deployment.
      </br>Chart.yaml: configures the chart name and version.</br>
      </br>templates:
       </br> - deployment.yaml: contains the deployment configuration.
       </br> - ingress.yaml: contains the ingress configuration.
       </br> - service.yaml: creates the nginx service on the node that runs the app.</br>