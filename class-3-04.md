[Reference Article](https://reactjs.org/docs/forms.html)

- HTML forms work differently than DOM forms in React because form elelements usually keep some internal state.

# Controlled Components
- in React, mutable state is typically kep in the state propert of components, and only updatwd with ```setState()```

- the HTML & React forms can be combined to be the "single source of truth"

Example given:

```
class NameForm extends React.Component {
  constructor(props) {
    super(props);
    this.state = {value: ''};

    this.handleChange = this.handleChange.bind(this);
    this.handleSubmit = this.handleSubmit.bind(this);
  }

  handleChange(event) {
    this.setState({value: event.target.value});
  }

  handleSubmit(event) {
    alert('A name was submitted: ' + this.state.value);
    event.preventDefault();
  }

  render() {
    return (
      <form onSubmit={this.handleSubmit}>
        <label>
          Name:
          <input type="text" value={this.state.value} onChange={this.handleChange} />
        </label>
        <input type="submit" value="Submit" />
      </form>
    );
  }
}
```
# Textarea Tag
```<textarea>```
- defines its text by its children
- in React, this tag uses a value attribute instead

# Select Tag
- allows you to update value in only one place



