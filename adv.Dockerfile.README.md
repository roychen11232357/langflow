2023/11/22
1. cd src/frontend
2. npm i
3. npm run build
4. cd ../..
5. 複製外部toolkit目錄到langflow/src/backend/langflow/components/toolkit下, ex. 
langflow/src/backend/langflow/components/toolkits/datainsight
6. docker build . -f adv.Dockerfile