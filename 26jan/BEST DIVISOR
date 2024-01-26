def digit_sum(n):
    return sum(map(int, str(n)))

def best_divisor(n):
    best_div = 1
    max_digit_sum = 1

    for i in range(2, n + 1):
        if n % i == 0:
            current_digit_sum = digit_sum(i)
            if current_digit_sum > max_digit_sum or (current_digit_sum == max_digit_sum and i < best_div):
                max_digit_sum = current_digit_sum
                best_div = i

    return best_div

# Input the integer
num = int(input().strip())

# Calculate and print the best divisor
result = best_divisor(num)
print(result)
