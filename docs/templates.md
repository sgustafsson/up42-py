# Workflow Templates

In addition to manually constructing workflows from blocks, the Python SDK allows you to
directly select from multiple preconfigured workflow templates. This will automatically 
add all required workflow tasks and also provide the optimal parameter configuration. 

Use the following commands to see the available templates:
```python
up42.get_templates()
```

And specify the workflow:

```python
workflow.add_template(template_name="ship-identification")
```

<br>

### Ship-Identification

<img align="left" src="https://metadata.up42.com/54217695-73f4-4528-a575-a429e9af6568/Block_Thumbnail_Ship_Identification1590606665498.png" alt="" width="150"/>

blockdiag {
   fontsize=10
   
   A -> B -> C -> D;
   
   A[label="Spot", numbered = 1];
   B[label="Tiling", numbered = 2];
   C[label="Ship-Detection", numbered = 3];
   D[label="Ship-Identification", numbered = 4];
}

### Ship-Detection

<img align="left" src="https://metadata.up42.com/54217695-73f4-4528-a575-a429e9af6568/Block_Thumbnail_Ship_Identification1590606665498.png" alt="" width="150"/>

blockdiag {
   fontsize=10
   
   A -> B -> C -> D;
   
   A[label="Spot", numbered = 1];
   B[label="Tiling", numbered = 2];
   C[label="Ship-Detection", numbered = 3];
   D[label="Ship-Identification", numbered = 4];
}
