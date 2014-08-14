Have the following construct in the language:

    if get_data() as data:
        # data is available here if the result of get_data() is truey
        # data contains the result of get_data()
    else:
        # data is available here though it'd be falsy

The reason, I write this way too often and it looks ugly:

    results = get_results()
    if results:
        pass