The Select component uses a modified dropdown component. See Dropdown for additional accepted props.

Select Example:

```jsx
import { Select, MenuItem } from 'ic-snacks'

; <Select
    name="country"
    floatingLabelText="Country"
    hintText="Select a country"
  >
    <MenuItem label="United States" value="US" />
    <MenuItem label="Canada" value="CA" />
  </Select>
```
