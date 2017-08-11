# Condition Evaluation Worksheet
With your chair pair, determine the final `boolean` output of these compound conditions. Refer to the _Truth Table_ and _Precedence List_ [here](05-compound-and-complex-conditionals.md).

```ruby
# let's do these first three together
puts 5 > 4 && false
puts true && 5 * 2 > 3 + 3 * 2
puts true && 5 * 2 > (3 + 3) * 2

#1
puts true && true || false
#2
puts true && (true || false)
#3
puts false && false || true
#4
puts false && (false || true)
#5
puts (false && false) && false && (true || false) || false

#6
puts 4 == "4"
#7
puts 4 == "4" || 4 == 4
#8
puts 10 % 3 == 10.0 % 3

#9
puts 10 * (5 / 2.0) == 10.0 * (5 / 2)
#10
puts 10 * 5 / 2 > 10 * (5 / 2)

#11
puts 2 * 2 ** 3 == (2 * 2) ** 3
#12
puts (10 - 4) < +6 || -(2 * -4) > 0
```
