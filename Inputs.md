# YAML Input Types

YAML (YAML Ain't Markup Language) supports various input types, allowing for flexible and readable data representation. Within the XADL framework, there are five key input types:

## Documents

```yml
input:
  documents:
    type: document
    label: Select Document(s)
```

This input type allows documents as inputs to the automation.

## Workspace

```yml
input:
  my_workspace:
    type: workspace
    label: Select Workspace
```

This input type allows the selection of a workspace as an input.

## Tags

```yml
input:
  selected_tags:
    type: tag
    label: Choose Tags
```

This input type allows the selection of tags as an input.

## Knowledge Sets

```yml
input:
  required_knowledge:
    type: knowledge_set
    label: Select Knowledge Sets
```

This input type allows the selection of knowledge sets as an input.

## Text

```yml
input:
  user_prompt:
    type: text
    label: Enter Your Query
```

This input type allows the entry of human text as an input.

**Note: The 'type' field is required and determines what can be selected/input from the user. The 'label' field provides a description or context for the input. The keys (documents, my_workspace, selected_tags, required_knowledge, user_prompt) can be any unique name chosen for the input and can be referenced in subsequent parts of the code.**