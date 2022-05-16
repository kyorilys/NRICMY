# NRICMY
Python NRIC Malaysia validator

There are 3 function validate_nric, validate_birth_place, and get_birth_date

validate_nric will return true if the NRIC malaysia is input correctly.

You just need call the function as the following

    
    from my_nric import validator


    def example():
        number = "910502-11-5298"
        is_nric_valid = validator.validate_nric(number)
    
        if is_nric_valid:
            print("Is Valid")
        else:
            print("Not Valid NRIC")


