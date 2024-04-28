# IFC-Cost-Item-Validation
Case study and useful outputs for the preparation of the paper developed to validate the BIM model containing cost information (IfcCostItem)

This study defines a new architecture for cost items within the Industry Foundation Classes (IFC) data model to ensure structured cost data, which is currently expressed in unstructured natural language. It encompasses the definition of a cost domain in IFC, potential relationships it may have with an IFC geometric information model, and the validation of these relationships through semi-automated verification procedures of structured data (geometric-cost). A specific case study, focused on a structural IFC model, is examined to assess current and future applications. Additionally, rules for BIM information requirements will be defined through the Information Delivery Specification (IDS) to ensure clear understanding for both humans and computers. This will specify which data must be included in the geometric model to ensure validation and verification of the uniqueness of associated cost data. The results demonstrate the feasibility of defining structured cost elements in IFC and verifying their association with geometric data to ensure coherence and uniqueness in cost estimation

The FlowChart is:

<img src="https://github.com/Cassa97/IFC-Cost-Item-Validation/assets/115898053/e08ca3d8-ea6d-44f8-858c-96679347161b" width="500" >  

The final BIM model with IfcCostitem (using FZK Viewer):

<img src="https://github.com/Cassa97/IFC-Cost-Item-Validation/assets/115898053/20aed8ae-02ac-4220-8407-c046c3653189" width="400" >

<!-- Due spazi alla fine dell'elemento precedente seguiti da un ritorno a capo -->



The IFC file with the new relations between object entities and cost entities can also be viewed through the USBIM viewer developed by ACCA. Below is the link to the page to view the otherwise downloadable template in the "IFC_output" folder.

[Updated IFC model](https://service.usbim.com/link/9WmVppDghIFzrXF6sdCchYI2)
