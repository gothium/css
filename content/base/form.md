+++
title = "Form"
description = "Form Styles of Gothium CSS"
+++

<details>
  <summary>Form Elements Styles</summary>

```scss
{{ include_code(path="sass/base/_form.scss") }}
```
</details>

## Form

<form>
        <label for="text">Text:</label>
        <input type="text" id="text" name="text">
        <!-- Password -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password">
        <!-- Email -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email">
        <!-- Number -->
        <label for="number">Number:</label>
        <input type="number" id="number" name="number">
        <!-- Tel -->
        <label for="tel">Telephone:</label>
        <input type="tel" id="tel" name="tel">
        <!-- URL -->
        <label for="url">URL:</label>
        <input type="url" id="url" name="url">
        <!-- Date -->
        <label for="date">Date:</label>
        <input type="date" id="date" name="date">
        <!-- Time -->
        <label for="time">Time:</label>
        <input type="time" id="time" name="time">
        <!-- datetime-local -->
        <label for="datetime-local">Date & Time:</label>
        <input type="datetime-local" id="datetime-local" name="datetime-local">
        <!-- month -->
        <label for="month">Month:</label>
        <input type="month" id="month" name="month">
        <!-- week -->
        <label for="week">Week:</label>
        <input type="week" id="week" name="week">
        <!-- radio -->
        <label for="radio1">Option 1:</label>
        <input type="radio" id="radio1" name="radio-group" value="1">
        <label for="radio2">Option 2:</label>
        <input type="radio" id="radio2" name="radio-group" value="2">
        <!-- checkbox -->
        <label for="checkbox">Check this:</label>
        <input type="checkbox" id="checkbox" name="checkbox">
        <!-- select -->
        <label for="simple-select">Simple Select:</label>
        <select id="simple-select" name="simple-select">
            <option value="option1">Option 1</option>
            <option value="option2">Option 2</option>
            <option value="option3">Option 3</option>
        </select>
        <!-- select > optgroup -->
        <label for="grouped-select">Grouped Select:</label>
        <select id="grouped-select" name="grouped-select">
            <optgroup label="Group 1">
                <option value="g1o1">Group 1 - Option 1</option>
                <option value="g1o2">Group 1 - Option 2</option>
            </optgroup>
            <optgroup label="Group 2">
                <option value="g2o1">Group 2 - Option 1</option>
                <option value="g2o2">Group 2 - Option 2</option>
            </optgroup>
        </select>
        <!-- datalist -->
        <label for="datalist">Choose an option:</label>
        <input list="datalist-options" id="datalist" name="datalist">
        <datalist id="datalist-options">
            <option value="Option A">
            <option value="Option B">
            <option value="Option C">
        </datalist>
        <!-- button -->
        <button type="submit">Submit</button>
        <button type="reset">Reset</button>
        <button type="button" onclick="alert('Button clicked!')">Click Me</button>
        <!-- file -->
        <label for="file">Upload a file:</label>
        <input type="file" id="file" name="file">
        <!-- range -->
        <label for="range">Select a range:</label>
        <input type="range" id="range" name="range" min="0" max="100">
        <!-- color -->
        <label for="color">Choose a color:</label>
        <input type="color" id="color" name="color">
        <!-- hidden -->
        <label for="hidden">Hidden value (invisible to users):</label>
        <input type="hidden" id="hidden" name="hidden" value="secretValue">
        <!-- image -->
        <label for="image">Submit with an image:</label>
        <input type="image" id="image" name="image" src="submit-button.png" alt="Submit Image">
        <!-- textarea -->
        <label for="textarea">Textarea:</label>
        <textarea id="textarea" name="textarea" rows="4" cols="50">Enter your text here...</textarea><br>
        <button disabled>Disabled</button>
    </form>

<form>
  <fieldset>
    <legend>Give us your feedback</legend>
    <label for="full-name">Full Name</label>
    <input class="w-full" name="full-name" id="full-name" type="text" placeholder="e.g Harry" required>
    <label for="email-address">Email Address</label>
    <input class="w-full" name="email-address" id="email-address" type="email" autocomplete="username" required>
    <label for="message">Message</label>
    <textarea class="w-full" rows="4" name="message" id="message" type="text" required></textarea><br>
    <button class="w-full" type="submit" value="Submit">Submit</button>
  </fieldset>
</form>
