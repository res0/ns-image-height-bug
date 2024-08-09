<template>
    <Page>
        <ActionBar>
            <Label text="NS Android Image height bug"/>
        </ActionBar>
        <GridLayout>
            <StackLayout style="padding: 15 0;">
                <Image
                    src="~/images/test.jpg"
                    style="border-width: 10;border-color:red;width:80%;height:auto;"
                />
            </StackLayout>
        </GridLayout>
    </Page>
</template>

<script>
  export default {};
</script>

<style scoped lang="scss">
</style>
