# YAML Input Types

YAML (YAML Ain't Markup Language) supports various input types, allowing for flexible and readable data representation. Common input types include:

Within the XADL framework, there are four key input types:

## Documents

```yml
input:
  documents:
    type: document
    label: Document
```

This code instructs XADL to allow a document or documents as inputs to the automation.

Type is a required field and indicates the type of input. This determines what can be selected/input from the user when activating the automation.

The label allows the user to indicate the purpose or description of the input.

## Workspace

```yml
input:
  my_workspace:
    type: workspace
    label: Select Workspace
```
Indicates that the user can select a workspace as an input when activating the automation. The label field provides a description for this input.

## Tags

```yml
input:
  selected_tags:
    type: tag
    label: Choose Tags
```
Indicates that the user can select tags as an input when activating the automation. The label field describes the purpose of this input.

## Knowledge Sets

```yml
input:
  required_knowledge:
    type: knowledge_set
    label: Select Knowledge Sets
```
Indicates that the user can select knowledge sets as an input when activating the automation. The label field provides context for this input.

## Text

```yml
input:
  user_prompt:
    type: text
    label: Enter Your Query
```
Indicates that the user can enter human text as an input when activating the automation. The label field guides the user on what to enter.

**Note: The keys (my_workspace, selected_tags, required_knowledge, user_prompt) can be any unique name the user chooses for the input. These names can be referenced in subsequent parts of the code.**