# pacletCICD
This will be to help me understand continuous integration and deployment based on the paclet at https://resources.wolframcloud.com/PacletRepository/resources/Wolfram/PacletCICD/tutorial/LicenseEntitlementsAndRepositorySecrets.html
I got an error of Failure["WorkflowExport::ymlconv", <|"MessageParameters" :> {
Wolfram`PacletCICD`Workflow[<|"Name" -> "My Workflow", 
      "On" -> <|"Push" -> <|"Branches" -> "test-branch"|>, 
        "WorkflowDispatch" -> True|>, 
      "Jobs" -> <|"DoTheThing" -> <|"Steps" -> {"Checkout", 
            "BuildPaclet"}|>|>|>, <||>]}, 
  "MessageTemplate" :> MessageName[
   Wolfram`PacletCICD`WorkflowExport, "ymlconv"]|>]
