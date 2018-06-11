def condition arr, const, sum
 arr.combination(const).to_a.select{|a| a.reduce(:+) == sum} 
end
