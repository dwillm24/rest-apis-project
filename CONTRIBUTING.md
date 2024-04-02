# CONTRIBUTING

## Docker commands

## How to build Docker image
```
docker build -t flask-smorest-api .
```

## How to run Docker file locally

```
docker run -dp 5000:5000 -w /app -v "$(pwd):/app" teclado-site-flask sh -c "flask run --host 0.0.0.0"
```

## Git commands

# Get status of files in working area and staging area
```
git status
```

# Add files to staging area
```
git add <filename>
```

# Add all files to staging area
```
git add .
```

# Commit files that are in staging area

```
git commit
```

# Commit all files that have been part of a previous commit
```
git commit -a
```

# Checkout file from latest commit and undo changes of file in working area
```
git checkout <filename>
```

# Remove file from staging area
```
git reset HEAD models/user.py
```