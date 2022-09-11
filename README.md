# Geometry Language Dataset

Dataset that content natural language and Geometry language to construct.

```json
[
  {
    "id": "c6t48f6h2921351_orthocenter_and_circumcenter",
    "problem": "Let ABC be an acute triangle with circumcenter O and orthocenter H. D is a point on segment AC, such that DH perp AC. Take E on BC such that DE perp OD. Prove that angle EHD = angle ACB",
    "construct": "ABC\nO = circumcenter(ABC)\nH = orthocenter(ABC)\nD = perpendicular_intersect(D, AC)\nE = perpendicular_intersect(D, OD)"
  }
]
```

## Contributing

Pull requests are welcome. For major changes,
please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
