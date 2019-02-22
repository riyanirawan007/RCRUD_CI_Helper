# RCRUD CI Helper
RCRUD CI Helper is helper for basic crud function, you don't need to create many function for every basic crud on table, this helper will auto generate table field for basic crud function. Return of each function is same as return on basic CI return type.

## USAGE
- Use this helper in CI models/ directly on controller
- Put on application/helper

## BASIC EXAMPLES
- Get Data From table_name
<br/><code>
  rcrud_get("table_name");</code>
<br>

- Add Data From table_name (POST), you just have to make form that have same name value as table field
<br><code>
  rcrud_add("table_name");</code>
<br>

- Edit Data From table_name (POST), you just have to make form that have same name value as table field
<br><code>
  rcrud_edit("table_name",array("id"=>1,"field1"=>field1));</code>
<br>

- Delete Data From table_name (POST), you just have to make form that have same name value as table field
<br><code>
  rcrud_delete("table_name",array("id"=>1));</code>
<br>
