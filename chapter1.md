# Chapter1

## Section 1
Some content.

First code example.

Here is an inline code example `x = y+1`

Here is some multiline code:

```matlab
for i=1:10
  disp(i)
end
```

Here is some math:
$$ y=1/x $$



{% exercise %}
Define a variable `x` equal to 10.
{% initial %}
var x =
{% solution %}
var x = 10;
{% validation %}
assert(x == 10);
{% context %}
// This is context code available everywhere
// The user will be able to call magicFunc in his code
function magicFunc() {
    return 3;
}
{% endexercise %}