  if (country === 'CAN' || country === 'Canada') {
    const regex = new RegExp('^[A-Za-z]\\d[A-Za-z][ -]?\\d[A-Za-z]\\d$');
    return regex.test(zipcode);
  } else if (country === 'USA' || country === 'United States') {
    const regex = new RegExp('^\\d{5}(-\\d{4})?$');
    return regex.test(zipcode);
  }
