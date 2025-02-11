---
title: Create a mapping data flow
description: How to create an Azure Data Factory mapping data flow
author: kromerm
ms.author: makromer
ms.service: data-factory
ms.subservice: data-flows
ms.topic: conceptual
ms.custom: seo-lt-2019
ms.date: 07/05/2021
---

# Create Azure Data Factory Data Flow

[!INCLUDE[appliesto-adf-xxx-md](includes/appliesto-adf-xxx-md.md)]

[!INCLUDE[data-flow-preamble](includes/data-flow-preamble.md)]

Mapping Data Flows in ADF provide a way to transform data at scale without any coding required. You can design a data transformation job in the data flow designer by constructing a series of transformations. Start with any number of source transformations followed by data transformation steps. Then, complete your data flow with sink to land your results in a destination.

Get started by first creating a new V2 Data Factory from the Azure portal. After creating your new factory, select "Open" in the "Open Azure Data Factory Studio" tile to launch the Data Factory UI.

:::image type="content" source="media/data-flow/v2portal.png" alt-text="Screenshot shows the New data factory pane with V2 selected for Version.":::

Once you are in the Data Factory UI, you can use sample Data Flows. The samples are available from the ADF Template Gallery. In ADF, select "Pipeline templates" tile in the 'Discover more' section of the homepage, and select the Data Flow category from the template gallery.

:::image type="content" source="media/data-flow/template.png" alt-text="Screenshot shows the Data Flow tab with Transform data using data flow selected.":::

You will be prompted to enter your Azure Blob Storage account information.

:::image type="content" source="media/data-flow/template2.png" alt-text="Screenshot shows the Transform data using data flow pane where you can enter User Inputs.":::

[The data used for these samples can be found here](https://github.com/kromerm/adfdataflowdocs/tree/master/sampledata). Download the sample data and store the files in your Azure Blob storage accounts so that you can execute the samples.

## Create new data flow

Use the Create Resource "plus sign" button in the ADF UI to create Data Flows.

:::image type="content" source="media/data-flow/newresource.png" alt-text="Screenshot shows Data Flow selected from the Factory Resources menu.":::

## Next steps

Begin building your data transformation with a [source transformation](data-flow-source.md).
