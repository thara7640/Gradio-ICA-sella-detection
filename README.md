# Gradio-ICA-detection
Gradio for ICA detection in endoscopic transsphenoidal surgery
# Step for using Gradio application for ICA detection 
1. Download all files on your PC/laptop (1.Gradio for ICA detection.ipynb, 2.ICA.yaml, 3.best.pt)
2. Open ICA detection.ipynb with google colab 
3. Run codes of StepA and StepB in colab
4. At the sidebar on the left side, you will see the yolov5 folder.
5. In the director of yolov5/data, drag to copy "ICA.yaml" in the "data" folder.
6. In the directory of yolov5/models, drag and copy "best.pt" into the "models" folder.
7. In the "models" folder, double-click on "yolov5s.yaml" to edit some code.
8. In the "yolov5s.yaml" file, edit "NC: 80" to "NC: 2"
9. Run codes of StepC in colab
10. Run codes of StepD in colab for Gradio interface by image; then: you will geta  public URL for external use with another window tab or mobile phone
11. Run codes of StepD in colab for Gradio interface by vdo.mp4 
# Download the illustration file to use the Gradio application for ICA detection as file.pdf
