# Table-with-HTML-CSS
##HTML##
<!DOCTYPE html>
<html>
<head>
  <title>Student Mark Sheet</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <table>
    <caption>88 STUDENTS MARK SHEET</caption>
    <thead>
      <tr>
        <th>Name</th>
        <th>Maths</th>
        <th>Science</th>
        <th>English</th>
        <th>Physics</th>
        <th>General Knowledge</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>David</td>
        <td>85</td>
        <td>87</td>
        <td>88</td>
        <td>92</td>
        <td></td>
      </tr>
      <tr>
        <td>Richard</td>
        <td>91</td>
        <td>81</td>
        <td>78</td>
        <td>71</td>
        <td>74</td>
      </tr>
      <tr>
        <td>John</td>
        <td>81</td>
        <td>86</td>
        <td>88</td>
        <td>84</td>
        <td>92</td>
      </tr>
      <tr>
        <td>Tony</td>
        <td>84</td>
        <td>86</td>
        <td>87</td>
        <td>82</td>
        <td>81</td>
      </tr>
      <tr>
        <td>Scott</td>
        <td>71</td>
        <td>79</td>
        <td>82</td>
        <td>88</td>
        <td>89</td>
      </tr>
    </tbody>
  </table>
</body>
</html>



##CSS##
table {
  border-collapse: collapse;
  width: 100%;
}

caption {
  font-size: 1.5em;
  font-weight: bold;
  padding: 10px;
}

th, td {
  padding: 10px;
  border: 1px solid #ddd;
  text-align: left;
}

th {
  background-color: #f2f2f2;
}
