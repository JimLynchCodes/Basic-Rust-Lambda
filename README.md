# Basic-Rust-Lambda
Just da basics...


# To Run Locally

Make sure you install serverless dependencies (only need to do this once):
```
npm i
```

Then, inside of the `basic-rust-lambda` directory, invoke locally (be sure to pass `local` with your invoke command):
```
npx serverless invoke local -f hello -d "$(cat local-invoke-payload.json)"
```

# Scaffolding

Scaffolded with (softprops/serverless-aws-rust-http)[https://github.com/softprops/serverless-aws-rust-http] with this command:
```
npx serverless install \
  --url https://github.com/softprops/serverless-aws-rust-http \
  --name my-new-api
```
