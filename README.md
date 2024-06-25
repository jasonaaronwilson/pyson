# The Pyson Data Format

`pyson` is a human readable data format similar to JSON though I contend it easier to read than either JSON or even my favorite my "s-expressions".

`pyson` looks like this snippet:

```
declaration[6]:
    tag: PARSE_NODE_STRUCT
    name: signed_fields_t
    field[0]:
        tag: PARSE_NODE_FIELD
        name: short_field
        type:
            tag: PARSE_NODE_TYPE
            type_node_kind: TYPE_NODE_KIND_TYPENAME
            type_name: short
    field[1]:
        tag: PARSE_NODE_FIELD
        name: short_int_field
        type:
            tag: PARSE_NODE_TYPE
            type_node_kind: TYPE_NODE_KIND_PRIMITIVE_TYPENAME
            type_name: short
```
