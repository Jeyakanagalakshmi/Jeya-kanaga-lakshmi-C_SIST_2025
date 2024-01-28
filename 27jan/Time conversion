def timeConversion(s):
    # Extract hours, minutes, seconds, and AM/PM from the input string
    hours, minutes, seconds = map(int, s[:-2].split(':'))
    am_pm = s[-2:]

    # Convert to 24-hour format
    if am_pm == 'PM' and hours < 12:
        hours += 12
    elif am_pm == 'AM' and hours == 12:
        hours = 0

    # Format the result
    result = '{:02d}:{:02d}:{:02d}'.format(hours, minutes, seconds)
    return result

# Example usage:
input_time = input()
output_time = timeConversion(input_time)
print(output_time)
