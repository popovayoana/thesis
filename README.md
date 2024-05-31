

Welcome to the body of your dataset site. Everything above this section is part of the Data package front matter. 

# Overview

Here is a quick overview of the template structure:

![[Overview.png]]

## Structured data

```mermaid
  graph TD;
      Data-Package-Frontmatter-->Dataset-title
      Data-Package-Frontmatter-->Data-package-metadata
      Data-Package-Frontmatter-->Short-description;
      Data-Package-Frontmatter-->Data-files-list;
      Data-Package-Frontmatter-->Data-Previews;
```

Feel free to customize the data package frontmatter accordingly when publishing your own data. 

## Unstructured data

You can add as many markdown files to your GitHub repository as you like, and you can freely nest them in subdirectories. You can also enhance your content with other data visualisation components and markdown features.

> Note: For a full list of supported markdown features visit https://flowershow.app/docs/syntax

Here are some quick examples:

> [!info] This is cool!
> Here's a callout block.
> It supports **markdown** and [[Internal link|wikilinks]].

Or you can quickly embed a piece of code as follows:

```
const ExampleCode = () => {
  return <div> .... </div>;
};
```

## To read more about how this works, refer to the [docs page](docs).

## Data Analysis

<PlotlyBarChart
  data={{
    url: '../data/frequency-age.csv'
  }}
  title="Correlation between age and frequency"
  xAxis="Age"
  yAxis="Frequency"
/>

