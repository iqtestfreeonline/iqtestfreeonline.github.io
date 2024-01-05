# IQ Test Free Online - Instant Results<!-- omit in toc -->

IQ Test is a standardized test to assess a person's intelligence. The test contains 30 questions to test your numerical, logical, spatial, and problem-solving skills. As you take the test, you can find out your IQ score compared to people of your age and see where you stand in the world. 
Take the <a href="https://iqtestonline.io/">iq test</a> right now and unleash your brain power!
Wondering what is my IQ? Give the test a try!


> **Note**
>
> People are always curious about their intelligence and IQ tests reflect some parts of this.
>
> IQ is short for intelligence quotient. It's supposed to gauge how well you use information and logic abilities to answer questions. 
> What's the purpose of IQ test?
>- To help you indentify how well you can perform in education program
>- To measure a set of skills like numerical, logical, problem-solving, and more. 


## Features

- Free
- Accurate
- Online
- Instant Results
- No registration
- Different intelligence abilities assessed!
- Expert-designed test
- Friendly


## Project Overview
**Understanding IQ**
IQ test is useful in clinical practice and education. However, your IQ score is not everything. It isn't the only factor that can decide whether you will be successful in life or not. There are many important factors like motivation, ambition, environment, and more. 

### Important files and folders

| File(s)                                     | Description                                              |
| ------------------------------------------- | -------------------------------------------------------- |
| `sanity.config.ts`                          |  Config file for Sanity Studio                           |
| `sanity.cli.ts`                             |  Config file for Sanity CLI                              |
| `/pages/studio/[[...index]].tsx`            |  Where Sanity Studio is mounted                          |
| `/pages/api/revalidate.ts`                  |  Serverless route for triggering ISR                     |
| `/pages/api/draft.ts`                       |  Serverless route for triggering Draft mode              |
| `/schemas`                                  |  Where Sanity Studio gets its content types from         |
| `/plugins`                                  |  Where the advanced Sanity Studio customization is setup |
| `/lib/sanity.api.ts`,`/lib/sanity.image.ts` | Configuration for the Sanity Content Lake client         |
| `/components/PreviewProvider.tsx`           | Configuration for the live Preview Mode                  |

## Configuration

### Step 1. Set up the environment

Use the Deploy Button below. It will let you deploy the starter using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=next-sanity-example) as well as connect it to your Sanity Content Lake using [the Sanity Vercel Integration][integration].

[![Deploy with Vercel](https://vercel.com/button)][vercel-deploy]

### Step 2. Set up the project locally

[Clone the repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) that was created for you on your GitHub account. Once cloned, run the following command from the project's root directory:

```bash
npx vercel link
```

Download the environment variables needed to connect Next.js and the Studio to your Sanity project:

```bash
npx vercel env pull
```

### Step 3. Run Next.js locally in development mode

```bash
npm install && npm run dev
```

When you run this development server, the changes you make in your frontend and studio configuration will be applied live using hot reloading.

Your blog should be up and running on [http://localhost:3000][localhost-3000]! You can create and edit content on [http://localhost:3000/studio][localhost-3000-studio].

### Step 4. Deploy to production

To deploy your changes to production you use `git`:

```bash
git add .
git commit
git push
```

Alternatively, you can deploy without a `git` hosting provider using the Vercel CLI:

```bash
npx vercel --prod
```

## Questions and Answers

### It doesn't work! Where can I get help?

In case of any issues or questions, you can post:

- [GitHub Discussions for Next.js][vercel-github]
- [Sanity's GitHub Discussions][sanity-github]
- [Sanity's Community Slack][sanity-community]

### How can I remove the "Next steps" block from my blog?

You can remove it by deleting the `IntroTemplate` component in `/components/IndexPage.tsx`.

### How can I set up Incremental Static Revalidation?

Go to the serverless function code in `/pages/api/revalidate.ts`. In the code comments, you'll find instructions for how to set up [ISR][vercel-isr].

## Next steps

