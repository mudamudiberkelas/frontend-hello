### `npm start`
### `npm test`
### `npm run build`

# Running Docker
docker run -it -p 3000:3000 IMAGE_ID
# Bookmarking Volumes
docker run -it -p 3000:3000 -v /app/node_modules -v $(pwd):/app 44b61c17a8c6
# Running With Script Test
docker run -it 44b61c17a8c6 npm run test
