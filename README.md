# gentestdef process_data(data_list):
    """A simple function that processes a list of integers."""
    if not isinstance(data_list, list):
        raise ValueError("Input must be a list")
    
    # Example logic: multiply even numbers by 2
    return [x * 2 for x in data_list if isinstance(x, int)]
